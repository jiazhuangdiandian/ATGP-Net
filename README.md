# ATGP-Net:Adaptive Texture-Guided Precision Segmentation Network for Breast Cancer Ultrasound Image
## Abstract
Breast cancer remains a leading cause of female mortality worldwide, with early detection through ultrasound imaging playing a crucial role. However, segmenting breast cancer tumors accurately is challenging due to their blurred boundaries and irregular shapes. To address this, we introduce the Adaptive Texture-Guided Precision Segmentation Network (ATGP-Net), a novel approach for breast cancer ultrasound image segmentation. ATGP-Net incorporates three key modules: Dual-Axis Self-Calibrating Attention (DASCA) for enhanced spatial feature reconstruction, Adaptive Information Fusion Module (AIFM) for improved channel information modeling, and Multiscale Edge-Enhanced Gradient Alignment Module (MEEGA) for precise edge detection. Experiments on three publicly available datasets demonstrate that ATGP-Net outperforms cur-rent advanced methods, achieving significant improvements in loU (as high as 63.56%) and Dice coefficient (as high as 76.68%). Our approach presents a robust solution for accurate breast cancer segmentation, contributing to earlier detection and improved patient outcomes. Our code is available at https://github.com/jiazhuangdiandian/ATGP-Net.git.
## framework diagram
![](https://github.com/jiazhuangdiandian/ATGP-Net/blob/master/img/1.jpg "framework diagram")
## Segmentation results
![](https://github.com/jiazhuangdiandian/ATGP-Net/blob/master/img/2.jpg "Segmentation results")
## Environment
1.Clonee thin repo:https://github.com/jiazhuangdiandian/ATGP-Net.git

2.Create a new conda environment and install dependencies:

pip:
```
-addict==2.4.0
-dataclasses=-0.8
-mmcv-full==-1.2.7
-numpy==1.19.5
-opencv-python==4.5.1.48
-perceptual=-0.1
-pillow==8.4.0
-scikit-image==0.17.2
-scipy==1.5.4
-tifffile==2020.9.3
-timm==0.3.2
-torch==1.7.1
-torchvision==0.8.2
-typing-extensions==4.0.0
-yapf==0.31.0
```
## Training & Test
Python train.py

Python val.py
## Dataset
Breast Ultrasound Dataset B: https://helward.mmu.ac.uk/STAFF/M.Yap/dataset.php

Breast Ultrasound Images (BUSI)：https://github.com/hugofigueiras/Breast-Cancer-Imaging-Datasets

BLUI:https://qamebi.com/breast-ultrasound-images-database/
