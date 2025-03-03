# Digital Image Processing Labs

## 📌 Introduction
This repository contains six laboratory exercises on **Digital Image Processing (DIP)** and **Image Spatial Processing (ISP)**, covering fundamental image transformations, filtering techniques, frequency domain analysis, feature extraction, morphological operations, and geometric transformations. These labs are implemented using Python with OpenCV and Scikit-Image libraries.

## 📂 Lab Summaries

### **1️⃣ Lab 01 - Basic Image Processing**
- Convert images to grayscale.
- Extract RGB and HSV channels.
- Apply hue thresholding to segment objects.
- Display histograms of color channels.
- Perform histogram equalization and brightness adjustment.
- Edge detection using Canny.

### **2️⃣ Lab 02 - Image Transformations & Feature Extraction**
- Analyze image properties (size, channels, intensity values).
- Convert between RGB and HSV color spaces.
- Extract bit-plane representations of color channels.
- Detect edges using Sobel, Laplacian, Prewitt, and Roberts operators.
- Color segmentation based on RGB values.
- Apply transformations: rotation, flipping, contrast enhancement, gamma correction.

### **3️⃣ Lab 03 - Image Blurring & Sharpening**
- Blur images using 3x3 and 5x5 mean filters.
- Measure image sharpness using Laplacian variance.
- Sharpen images with custom kernels.
- Implement automatic blur detection.
- Analyze RGB max intensity regions.
- Apply masks for color region segmentation.

### **4️⃣ Lab 04 - Frequency Domain Processing**
- Apply Discrete Fourier Transform (DFT) and Discrete Cosine Transform (DCT).
- Create masks to remove high/low-frequency components.
- Recover images from the frequency domain.
- Compare image compression efficiency using DCT vs. DFT.

### **5️⃣ Lab 07 - Morphological Image Processing**
- **Dilation**: Expanding bright regions in a binary image.
- **Erosion**: Shrinking bright regions in a binary image.
- **Closing**: Filling small holes in bright regions.
- **Opening**: Removing small noise from images.
- **Gradient**: Extracting edges using dilation and erosion difference.
- **Real-world applications**:
  - Extracting numbers from license plates.
  - Extracting store information from signboard images.

### **6️⃣ Lab 08 - Geometric Transformations**
- **Scaling**: Resizing images.
- **Translation**: Moving images.
- **Rotation**: Rotating images at various angles.
- **Shearing**: Distorting images horizontally or vertically.
- **Affine Transformation**: Combining multiple transformations.
- **Perspective Transformation**: Adjusting image perspective.

## 🔧 Requirements
- Python 3.x
- OpenCV
- Scikit-Image
- NumPy
- Matplotlib

## 🚀 How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/hoangphuu/DIP_Labs.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run individual labs:
   ```sh
   python lab01.py  # Replace with lab02.py, lab03.py, etc.
   ```
