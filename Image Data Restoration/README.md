# Image Reconstruction using Random Fourier Features + Linear Regression, Matrix Factorization and Alternating Least Squares

This folder contains implementations for image reconstruction tasks using matrix factorization, Alternating Least Squares (ALS) and Random Fourier Features (RFF) with Linear Regression. The goal is to reconstruct images with missing or corrupted data and evaluate the quality of the reconstructions using various metrics.

## Tasks Completed

### Task 1: Completing Image with Random Missing Data using RFF + Linear regression
- Applied Random Fourier Features to complete the image with missing data ranging from 10% to 90%.
- Displayed the reconstructed images for each missing data percentage and computed metrics such as RMSE and PSNR.

### Task 2: Image Reconstruction using Matrix Factorisation
#### Part (1)
- Reconstructed the image with missing regions:
  - A rectangular block of size 30x30
  - A random subset of 900 pixels
- Used Gradient Descent until convergence for reconstruction.
- Compared reconstructions using ALS and RFF + Linear Regression.
- Plotted the selected regions, original, and reconstructed images.
- Computed metrics such as RMSE and PSNR.

#### Part (2)
- Varied region size (NxN) for N = [20, 40, 60, 80].
- Performed Gradient Descent till convergence for each region size.
- Considered both cases of missing regions (rectangular block and random subset).
- Demonstrated variation in reconstruction quality with appropriate plots and metrics.

### Task 3: Image Reconstruction using Alternating Least Square method
- Implemented a function using ALS for image reconstruction.
- Repeated Part 1 and 2 of Task 5 using the ALS function.
