# Haze Removal

## Introduction

This is an simple implemention of "single image haze removal using dark channel prior" by kaiming He, which wins the CVPR09 best paper.

## Parameters by default
- radius=7
- omega=0.95
- t0=0.1
- r=60
- eps=0.001

## Dependencies

- numpy
- opencv-python
- scikit-image
- Pillow
- matplotlib
- numba

## Run

```bash or zsh
cd Haze_Removal_python
python haze_removal.py 
```
You should modify the 'image' in haze_removal.py according to your own testset

## DEMO

<figure class="half">
    <img src="IEI2019/H52.jpg">
    <img src="results/test20.jpg">
</figure>

<figure class="half">
    <img src="demo/canyon2.bmp">
    <img src="demo/canyon2_rev.jpg">
</figure>


## References

- paper: Single Image Haze Removal using Dark Channel Prior
- paper: Guided Image Fltering
