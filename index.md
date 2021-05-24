# Homework Assignment 4 

<p align='right'>
  2021314078 배은지
</p>

### HDR IMAGING

<figure>
<p align='center'>
  <img src='./image/01.PNG'">
  <figcaption>Fig 1. Two LDR exposures, and an HDR composite tonemapped using the photographic tonemapping
</p>
</figure>

<p align='center'>
  <img src='./image/dcraw.png' width="500px">
</p>
                                            


```matlab
list1 = impyramid(frame_list, 'reduce');
list2 = impyramid(list1, 'reduce');
list3 = impyramid(list2, 'reduce');
list4 = impyramid(list3, 'reduce');
```
