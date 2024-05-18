# Image Compression using Matrix Factorization

This folder contains implementations for image compression using matrix factorization techniques, specifically low-rank matrix factorization. The goal is to compress image patches efficiently by representing them with fewer parameters while retaining the essential features.

## Tasks Completed

### Data Compression
Considered image patches of size (NxN) where N=50 and explored the use of low-rank matrix factorization for compression in three cases:
1. Patch with mainly a single color.
2. Patch with 2-3 different colors.
3. Patch with at least 5 different colors.

Varying the low-rank value as r = [5, 10, 25, 50] for each case, reconstructed patches using Gradient Descent and plotted them over the original image. Demonstrated the difference in reconstruction quality.
