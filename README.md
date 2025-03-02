# Image Informatics Project
This repository contains the course project for CSC8628 Image Informatics at Newcastle University.

## Summary
This project focuses on image processing techniques, including wavelet transformation and image denoising.

### Tasks
1. **Image Reading and Displaying**
   - Implement a custom `imread()` function to read PGM images.
   - Display PGM images using standard visualization libraries.

2. **Wavelet Decomposition**
   - Develop a forward discrete wavelet transform (FDWT) using the Haar wavelet filter for 3-level decomposition.
   - Implement an inverse discrete wavelet transform (IDWT) for image reconstruction.
   - Validate reconstruction quality using Mean Square Error (MSE) measurement.

3. **Image Denoising**
   - Develop a custom wavelet-based image denoising algorithm.
   - Compare performance with traditional denoising methods, including mean filtering, median filtering, and wavelet-based denoising (e.g., VisuShrink, BayesShrink).
   - Evaluate denoising quality using MSE and Structural Similarity Index (SSIM).

### Files
- **Dataset**
  - Includes testing images and report documentation.
- **PGM_types**
  - Contains testing images and report documentation.
- **CSC8628_Chatwipa.ipynb**
  - Main code for the Image Informatics project.
