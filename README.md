# **Image Processing in MATLAB with GUI Design**

Welcome to the **Image Processing in MATLAB with GUI Design** project! This repository showcases an interactive application for digital image processing using MATLAB's **App Designer**. The project integrates various image filtering and manipulation techniques, with an easy-to-use graphical user interface (GUI).

## **Table of Contents**
- [Introduction](#introduction)
- [Features](#features)
- [Program Description](#program-description)
- [Scope and Limitations](#scope-and-limitations)
- [Visuals](#visuals)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Documentation](#documentation)
- [Conclusion](#conclusion)

## **Introduction**

Digital Signal Processing (DSP) is widely used to manipulate and analyze signals such as images, sound, and sensor data. This project focuses on processing image signals, such as filtering and enhancing images, using **MATLAB**. Users can:
- Apply different types of image filters (low-pass, high-pass, band-pass, and band-stop).
- Perform operations like brightness adjustment, rotation, flipping, and background removal.
- Convert images to grayscale, binary, RGB, and indexed formats.

This project demonstrates DSP techniques while showcasing a MATLAB GUI for interactive image processing.

## **Features**

1. **Filtering Techniques**:
   - Low-pass, high-pass, band-pass, and band-stop FIR filters.
2. **Image Manipulation**:
   - Brightness and contrast adjustment.
   - Rotation and flipping.
   - Background estimation and removal.
3. **Image Conversion**:
   - Grayscale, binary, RGB, indexed, and multi-frame images.
4. **Interactive GUI**:
   - User-friendly interface to process images step-by-step.
   - Reset functionality to revert changes.
   - Import and save processed images.

## **Program Description**

The GUI divides functionality into three filter categories, each displayed in a separate output panel:
1. **Category 1**: FIR filtering (sharpening, smoothing, denoising) and brightness adjustment.
2. **Category 2**: Image type conversions (grayscale, binary, RGB) and morphological background estimation.
3. **Category 3**: Indexed image processing, multi-framing, and contrast adjustment.

The GUI allows users to select an image, apply transformations, and view results in real time. A reset button enables users to clear filters without changing the sample image.

## **Scope and Limitations**

### **Scope**
- Import images from local files.
- Convert images between RGB, binary, grayscale, and indexed formats.
- Apply various filters and processing techniques.
- Save processed images for further use.

### **Limitations**
- Processes one image at a time.
- Limited to four FIR filter types.
- Some images may not process correctly due to size constraints (requires square matrix dimensions).
- Filtering cannot be applied sequentially; only one filter is active at a time.

## **Visuals**

### **Plain GUI**  
![Plain GUI](/GUI_Design.PNG)

### **Sample Processed Image**  
![Sample Processed Image](/Sample_Processing.png)

## **Getting Started**
- **MATLAB** with Image Processing Toolbox.  
  Download MATLAB here: [MATLAB Official Website](https://www.mathworks.com/products/matlab.html).

- **Procedure**
  Follow full project [procedure](/Project_Procedure.pdf) with instructions to create the design and the code.

## **Usage**

1. Open the project in MATLAB's App Designer.
2. Use the GUI to:
   - Import an image from your local machine.
   - Select filters, adjust parameters, and apply processing.
   - Save or reset images as needed.
3. Explore different filtering categories for varied results.

## **Documentation**

The complete step-by-step procedure for recreating this project, including detailed explanations and code walkthroughs, is available in the [Documentation](/Project_Documentation.pdf).  

## **Conclusion**

This project demonstrates the power of MATLAB's Image Processing Toolbox and GUI design capabilities for digital signal processing. By providing an intuitive interface, users can explore advanced image manipulation techniques with ease.

Happy coding!
