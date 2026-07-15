A comprehensive, production-ready library of Python and C/C++ implementations demonstrating core algorithms in Digital Signal Processing (DSP) and Digital Image Processing (DIP). 

This repository bridges theoretical mathematics and concrete code execution, optimizing for vectorized operations using `NumPy`, high-fidelity plotting via `Matplotlib`, computer vision pipelines through `OpenCV`, and real-time embedded DSP systems.

## Repository Architecture & Features

# Part 1: Digital Signal Processing (DSP):
 
 
* **Fundamental Time Sequences:** Modular generators for Unit Impulse (\delta[n]), periodic Impulse Trains (Dirac Combs), Unit Step (u[n]), Linear Ramp, decaying exponentials, and parabolic paths.
* **Convolutions & Transforms:** High-performance Full Linear Convolution compared directly against fast Circular Convolution utilizing Forward and Inverse Fast Fourier Transforms (`FFT`/`IFFT`).
* **Correlation Engineering:** Time-lagged mathematical matching using Autocorrelation and Cross-correlation models to evaluate signal similarity profiles.
* **Infinite Impulse Response (IIR) Filters:** Design architectures for Low-Pass Butterworth and Chebyshev Type-1 filters, mapped from analog space to the digital plane using the Bilinear Transformation Method.
* **Finite Impulse Response (FIR) Filters:** Truncated ideal low-pass filter synthesis optimized using standard windowing functions (e.g., Hamming window) with built-in coefficient normalization.

 # Part 2: Digital Image Processing (DIP):
 
* **Spatial Intensity Operations:** Grayscale transformations including global Histogram Equalization contrast adjustments, pixel brightness adjustments, image negation, and binary thresholding.
* **Histogram Optimization:** Distribution mapping, contrast stretching, and reference-driven Histogram Matching pipelines.
* **Spatial Filtering Matrix:** Low-pass linear blur matrix operations and high-pass edge-sharpening spatial convolutions (`filter2D`).
* **Non-Linear Noise Mitigation:** Statistical noise removal utilizing localized Median Blurring and edge-preserving Bilateral Filtering.
* **Frequency Domain Filtering:** Centered Gaussian Low-Pass filters for smooth artifact-free blurring and structural High-Pass masks executed via the Discrete Fourier Transform (`DFT`/`IDFT`).
* **Morphological Operators:** Structuring element pixel modifications for fundamental Dilation, Erosion, Opening, and Closing configurations.
* **Structural Feature Extraction:** Targeted pattern detection using the morphological Hit-or-Miss transformation and structural object boundary perimeter extraction.

# Part 3: Real-Time Audio Hardware Acquisition:
* **Embedded DSP Integration:** C/C++ audio processing scripts configuring system codecs (AIC23) for low-latency audio data buffer acquisition loops at standard high-fidelity frequencies (44.1 kHz / 48 kHz).
