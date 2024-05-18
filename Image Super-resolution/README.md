# Image Super-Resolution using Random Fourier Features and Linear Regression

This folder contains an implementation of image super-resolution using Random Fourier Features (RFF) and Linear Regression. The goal is to increase the resolution of a low-resolution image by learning a mapping from low-resolution to high-resolution images.

## Overview

The process involves the following steps:
1. Start with a ground truth high-resolution image (400x400).
2. Resize the high-resolution image to a low-resolution image (200x200), which serves as the input image.
3. Utilize Random Fourier Features (RFF) and Linear Regression to predict the high-resolution image from the low-resolution input image.
4. Evaluate the quality of the predicted high-resolution image using the following metrics:
    - Root Mean Squared Error (RMSE) between the predicted and ground truth high-resolution images.
    - Peak Signal-to-Noise Ratio (PSNR) between the predicted and ground truth high-resolution images.
