# Homework Assignment 4 

<p align='right'>
  2021314078 배은지
</p>

### HDR IMAGING
과제에 사용된 이미지의 특징
1. single exposure로 찍기 힘든 매우 다른 illumination과 dynamic range을 가진 영역이 있음
2. 두 영역 모두 결과의 색상 표현을 평가하는데 사용할 수 있는 여러 항목을 포함하고 있음
3. 결과의 해상도를 평가하는데 사용할 수 있는 높은 세부 기능 (lens/camera markings)
4. 색상 보정에 사용할 수 있는 색상 검사기가 있음

<p align='center'>
  <img src='./image/01.PNG'>
  <figcaption>Fig 1. Two LDR exposures, and an HDR composite tonemapped using the photographic tonemapping </figcaption>
</p>

<p align='center'>
  <img src='./image/dcraw.png' width="500px">
</p>
                                            

```matlab
list1 = impyramid(frame_list, 'reduce');
list2 = impyramid(list1, 'reduce');
list3 = impyramid(list2, 'reduce');
list4 = impyramid(list3, 'reduce');
```
