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

1. **Download the Dataset**  
   Download the Sports Image Classification dataset from Kaggle:  
   [Sports Image Classification Dataset](https://www.kaggle.com/datasets/sidharkal/sports-image-classification/data)

2. **Set Up Environment**  
   Install the required Python packages using the following command:  
   ```bash
   pip install -r requirements.txt
   ```
   
3. **Open Jupyter Notebook**  
   Navigate to the `notebooks/` directory and open the following files:
   - `Training_with_Gaussian_Pyramid.ipynb`
   - `NearestNeighborInterpolation.ipynb`
   - `Wavelet_Transform_Resampling.ipynb`
   - `datamining-3.ipynb`
   - `dataminingPart5.ipynb`

4. **Explore the Results**  
   Analyze the results through the plots and metrics provided in the notebooks.

---

## Contributions

- **Wonjoon Hwang**: Setup experiments and implemented SRCNN resampling.
- **Zhizheng Wang**: Implemented and evaluated Wavelet Transform resampling.
- **Khoa Le**: Conducted Bilinear and Bicubic Interpolation analysis.
- **Chih-Yuan Tung**: Explored Gaussian Pyramid resampling.
- **Brett Ruane**: Evaluated Nearest Neighbor Interpolation.

---

## References

1. Bashir, Syed Muhammad Arsalan, et al., "A comprehensive review of deep learning-based single image super-resolution." PeerJ Computer Science 7 (2021): e621.
2. Dong, Chao, et al., "Image super-resolution using deep convolutional networks." IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 38, no. 2, 2016, pp. 295–307. [DOI: 10.1109/TPAMI.2015.2439281](https://doi.org/10.1109/TPAMI.2015.2439281)
3. Mallat, S., & Hwang, W. L., "Singularity detection and processing with wavelets." IEEE Transactions on Information Theory, 38(2), 617–643. [DOI: 10.1109/18.119727](https://doi.org/10.1109/18.119727)
4. Rukundo, Olivier, and Hanqiang Cao, "Nearest neighbor value interpolation." arXiv preprint [arXiv:1211.1768](https://arxiv.org/abs/1211.1768) (2012).
5. Verma, Atul & Saini, Barjinder, "Forward-backward processing technique for image denoising using FDZP 2D filter." Journal of Applied Research and Technology, 15. [DOI: 10.1016/j.jart.2017.07.001](https://doi.org/10.1016/j.jart.2017.07.001)

---
