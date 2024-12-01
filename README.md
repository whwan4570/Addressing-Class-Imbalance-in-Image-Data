# Addressing Class Imbalance in Image Data: A Comparative Study of Resampling Techniques and Deep Learning Models

### Authors: Wonjoon Hwang, Zhizheng Wang, Khoa Le, Chih-Yuan Tung, Brett Ruane

## Overview

This repository contains code, notebooks, and supporting materials for the study on addressing class imbalance in image datasets. The study evaluates the performance of different resampling techniques and deep learning architectures on the Sports Image Classification dataset, highlighting the interplay between model architectures and resampling techniques.

---

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Resampling Techniques](#resampling-techniques)
- [Deep Learning Architectures](#deep-learning-architectures)
- [Results](#results)
- [How to Run](#how-to-run)
- [Contributions](#contributions)
- [References](#references)

---

## Introduction

Class imbalance in image datasets poses significant challenges in machine learning. This project investigates various resampling techniques, such as Nearest Neighbor Interpolation, Bicubic Interpolation, Gaussian Pyramid, SRCNN, and Wavelet Transform Resampling, in combination with deep learning architectures like GoogLeNet, ResNet50, AlexNet, and VGG16.

The findings emphasize the importance of selecting the appropriate resampling method for a given architecture to enhance classification performance.

---

## Project Structure

```plaintext
├── notebooks/
│   ├── Training with Gaussian Gaussian Pyramid.ipynb
│   ├── NearestNeighborInterpolation.ipynb
│   ├── Wavelet_Transform_Resampling.ipynb
│   ├── datamining-3.ipynb
│   ├── dataminingPart5.ipynb
├── Final Paper.pdf
├── README.md
└── LICENSE
```
---

## How to run

1. Download a Sports Image Classification data set from kaggle. https://www.kaggle.com/datasets/sidharkal/sports-image-classification/data

2. Open and run the notebooks

3. Explore results through provided plots and metrics.

---

## Contributions
- Wonjoon Hwang: Setup experiments and implemented SRCNN resampling.
- Zhizheng Wang: Implemented and evaluated Wavelet Transform resampling.
- Khoa Le: Conducted Bilinear and Bicubic Interpolation analysis.
- Chih-Yuan Tung: Explored Gaussian Pyramid resampling.
- Brett Ruane: Evaluated Nearest Neighbor Interpolation.

---

## References

• Bashir, Syed Muhammad Arsalan, et al. ”A compre- hensive review of deep learning-based single image super-resolution.” PeerJ Computer Science 7 (2021): e621.
• Dong, Chao, et al. ”Image super-resolution us- ing deep convolutional networks.” IEEE Transac- tions on Pattern Analysis and Machine Intelli- gence, vol. 38, no. 2, 2016, pp. 295–307, https://doi.org/10.1109/TPAMI.2015.2439281.
• Mallat, S., & Hwang, W. L. (1992). Singular- ity detection and processing with wavelets. IEEE Transactions on Information Theory, 38(2), 617–643. https://doi.org/10.1109/18.119727
• Rukundo, Olivier, and Hanqiang Cao. ”Near- est neighbor value interpolation.” arXiv preprint arXiv:1211.1768 (2012).
• Verma, Atul & Saini, Barjinder. (2017). Forward- backward processing technique for image denoising using FDZP 2D filter. Journal of Applied Research and Technology. 15. 10.1016/j.jart.2017.07.001.

