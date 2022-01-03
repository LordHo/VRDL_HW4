# VRDL HW4 - Image Super Resolution

## Deadline is 2022/01/03 23:59

## Task List

- [ ] Read class pdf
- [ ] Read HW4 introduction ppt
- [ ] Select Model
- [ ] Complete Dataset and Dataloader
- [ ] Training
- [ ] Testing
- [ ] Submit Result
- [ ] Finish README

## Carefully Things

- No allow pretrained model
- Peak signal to noise ratio (PSNR) is metric method
- Baseline performance in PSNR: 27.4162
  - Baseline model is VDSR [Kim etal. CVPR’16](https://cv.snu.ac.kr/research/VDSR/VDSR_CVPR2016.pdf)
  - Using Data-augmentation
  - Can see the SOAT on paperwithcode of [Image Super-Resolution](https://paperswithcode.com/task/image-super-resolution)
- Need to use bicubic interpolation
  - Difference interpolation may get wrost performance
  - Difference interpolation can use in data augmentation
- Some train data image size is smaller than the smallest input of model
- Upscale the test images with an upscaling factor of 3
  - Format is {test_img_name}_pred.png

## Introduction

## Installation

## Methodology

### Data pre-process

### Model architecture

### Hyperparameters

## Result

## Summary

## Model Weights

## Reference
