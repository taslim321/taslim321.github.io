---
title: Fourier Vision:- An interactive Matlab  App for Fourier series signal analysis and reconstruction
date: 2025-10-26
links:
  - type: site
    url: https://drive.google.com/drive/folders/1JXv2A47XJQiCiqK-liBIawg1oHxxDw9v?usp=drive_link
tags:
  - Fourier Vision
  - MATLAB
  - Project
---

    
Purpose/Objectives:

The purpose of this project is to design and implement a MATLAB-based
application that helps students and professionals in Electrical and Electronic
Engineering visualize and understand Fourier Series analysis.
The objectives are:
1. To create an interactive app where users can choose a periodic signal (square,
sawtooth, triangle).
2. To compute and display Fourier coefficients for the chosen signal.
3. To reconstruct the signal using a finite number of harmonics and visualize the
approximation accuracy.
4. To calculate and present the error between the original and reconstructed
signals.
This app serves as an educational tool, enabling students to intuitively grasp the
concept of Fourier decomposition and signal reconstruction.

Equipment/Software:
- Software: MATLAB App Designer (R2018).
- Numerical Technique Used: Fourier Series approximation (integration by
numerical trapezoidal rule).
- Functions Used:
- square(), sawtooth() → for generating periodic signals.
- trapz() → for numerical integration (Fourier coefficients, Gibbs phenomenon).
- uitable → to display coefficients.
- UI components (dropdown, slider, numeric edit field) in App Designer.
- plot() → for signal visualization.

Results and Discussion

Input Data:
- Signal Type: Square, Sawtooth, Triangle.
- Frequency (Hz): User-defined.
- Number of Harmonics (N): Adjustable via slider (1–50).

Output Data:
- Original signal plot.
- Reconstructed signal plot.
- Fourier coefficients (a0, an, bn).
- Error between original and reconstructed signal.

Performance:
- Increasing the number of harmonics improves reconstruction accuracy,
especially for discontinuous signals like the square wave.
- The app effectively demonstrates Gibbs phenomenon near discontinuities.
- Error decreases as harmonics increase, validating the convergence of Fourier
series.

Conclusion:
This project successfully designed a MATLAB-based interactive Fourier Series App,
which provides users with both theoretical and visual understanding of Fourier
decomposition. It can be used for an effective educational tool for signal analysis
in Electrical and Electronic Engineering .
<!--more-->
