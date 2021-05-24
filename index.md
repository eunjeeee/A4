# Homework Assignment 4 

<p align='right'>
  2021314078 배은지
</p>

### HDR IMAGING
- HDR (High Dynamic Range) imaging 및 tonemapping 탐색
- HDR imaging을 사용하여 scene radiance values에 선형으로 매핑되는 floating-point precision images 만듦
- 
<figure>
<p align='center'>
  <img src='./image/01.PNG'>
  <figcaption>Fig 1. Two LDR exposures, and an HDR composite tonemapped using the photographic tonemapping
</figure></p>


<p align='center'>
  <img src='./image/dcraw.png' width="500px">
</p>
                                            

```matlab
list1 = impyramid(frame_list, 'reduce');
list2 = impyramid(list1, 'reduce');
list3 = impyramid(list2, 'reduce');
list4 = impyramid(list3, 'reduce');
```
