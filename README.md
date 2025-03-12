# Visual Quality Enhancement in Low-Light Images: A Comparative Study of Enhancement Techniques

## Summary

Image enhancement is critical for improving the usefulness of images in various applications. This article focuses on how applying point operations and experimenting with combinations of them can improve the identification of relevant information in low-light images. 

To evaluate these techniques, low-light images from the **The Dark Face** dataset were used. The main goal of this study is to enhance these images using image processing techniques and to identify the limitations of each method. This approach provides a clear understanding of the capabilities and limitations of each technique in the context of image enhancement under low-light conditions. 

The results and discussions presented in this study offer valuable information for future research and development in this area. 

### Techniques used in this study include:
- **Linear, Logarithmic Transformations, and Gamma Correction**: These techniques improve the visibility of details, but they come with the risk of losing quality and generating noise.
- **Arithmetic Operations** (addition, multiplication, division): These can adjust the brightness, but **histogram equalization** can generate noise, especially in images with low light levels.

## Objectives

- Evaluate and compare various image enhancement techniques.
- Improve the visibility of relevant information in low-light images using point operations.
- Identify the limitations of each technique and provide a practical understanding of their applications.
- Explore the capabilities and constraints of different techniques in improving image quality under low-light conditions.

## Dataset

For this study, we used images from the **The Dark Face** dataset, which consists of low-light images that serve as the primary test data for evaluating enhancement techniques. 

### Key techniques evaluated:
- **Linear Transformation**
- **Logarithmic Transformation**
- **Gamma Correction**
- **Histogram Equalization**
- **Arithmetic Operations** (Sum, Multiplication, Division)

## 📚 Libraries Used

```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
from skimage import exposure
