# Optical Aberrations Modeling and Image Processing with Zernike Polynomials

This project explores the modeling of optical aberrations using Zernike Polynomials and their application to image processing techniques, specifically in the context of augmented reality (AR) and near-eye displays (NEDs). It leverages scientific computing frameworks such as PyTorch for convolution-based image simulation.

## Key Features

- **Zernike Polynomial Generator**: Generates the radial, azimuthal, and normalization components of Zernike polynomials used to model optical aberrations in imaging systems.
  
- **Convolution with PyTorch**: Applies convolutional neural network techniques using PyTorch's `conv2d` function to simulate how point spread functions (PSFs) affect image clarity and focus. This is analogous to the convolution operations commonly used in AI-based image recognition and processing.

- **Wavefront Error and PSF Visualization**: Utilizes `matplotlib` and `ipywidgets` for interactive visualization of Zernike polynomial coefficients and the resulting wavefront errors and point spread functions. These visualizations provide insights into how optical aberrations distort images, relevant for real-world AI and machine learning applications in image restoration.

## Technical Highlights

1. **Python & PyTorch**: Core computational framework for modeling the wavefront errors and simulating the point spread functions, leveraging GPU acceleration where applicable.
   
2. **Image Processing**: Demonstrates convolution of images with custom PSFs, which is essential in machine learning fields such as AI-based image denoising, enhancement, and object recognition.

3. **Fourier Transforms**: The project makes extensive use of 2D Fourier Transforms to compute PSFs, highlighting an important mathematical concept often used in AI for feature extraction and signal processing.

## Use Cases

- **Optical System Analysis**: Model and simulate optical aberrations for augmented reality systems.
  
- **AI Image Processing**: Understand how convolutional techniques used in AI can be applied to real-world optical systems and image degradation.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/ahmedadamji/Optical-Aberrations-Modeling.git
   ```
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to explore the Zernike Polynomial generator and visualizations:
   ```
   jupyter notebook
   ```


## License
**This project is licensed under the MIT License.**





