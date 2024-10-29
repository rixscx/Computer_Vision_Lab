# Computer_Vision_Lab
##  Image Processing Techniques: Edge Detection and Frequency Analysis
# Original Image:
![M_U](https://github.com/user-attachments/assets/ca6c9967-b3f8-43d3-af02-f3caaf7a1c65)

## 🚀 Overview
The notebook covers several computer vision tasks using OpenCV and Matplotlib. Here are some key operations included in the notebook:  
Sobel Edge Detection, Gaussian Blurring, Gabor Filtering, Laplacian Edge Detection, Fourier Transform, Non-Maximum Suppression.

> **Goal:** To visualize and explore different ways of identifying edges and frequency components in images.

# Computer Vision Lab - Edge Detection and Filtering Techniques

This repository provides a Jupyter Notebook showcasing various computer vision techniques using OpenCV and Python. The notebook demonstrates edge detection, image filtering, and texture analysis on grayscale images. Techniques include Sobel and Laplacian edge detection, Gaussian and Gabor filtering, Fourier Transform, and Non-Maximum Suppression.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## **Usage**

Open the Jupyter Notebook: Start Jupyter Notebook and open cv_lab5.ipynb:

```bash
        jupyter notebook cv_lab5.ipynb
```
**Run the Cells:** Follow the cells in the notebook to visualize each step of edge detection and filtering techniques.

Example Outputs

### **Sobel Edge Detection:**
Displays the original image alongside edges detected in the X and Y directions and their combination.

### **Gaussian Blurring:**
Shows the effect of Gaussian blurring on a grayscale image.

### **Gabor Filtering:**
Visualizes texture analysis at multiple orientations.

### **Laplacian Edge Detection:**
Highlights edges using the Laplacian operator.

### **Fourier Transform:**
Computes and displays the magnitude spectrum.

### **Non-Maximum Suppression:**
Refines Sobel edge detection results by suppressing non-maximum values.

## Features

1. **Sobel Edge Detection**: Detects edges in X and Y directions.
2. **Gaussian Blurring**: Reduces image noise with a Gaussian filter.
3. **Gabor Filtering**: Analyzes texture with directional Gabor filters.
4. **Laplacian Edge Detection**: Applies Laplacian to highlight edges.
5. **Fourier Transform**: Computes and displays the frequency spectrum.
6. **Non-Maximum Suppression**: Suppresses non-maximum edges to refine results.

## **Project Structure**
```
computer-vision-lab/
│
├── cv_lab5.ipynb          # Jupyter Notebook with all image processing techniques
├── requirements.txt       # List of dependencies
└── README.md              # Project documentation
```

## Installation


If the repository URL is known or is for a specific organization, it can be directly specified:

```markdown
## Installation
```
1. **Clone the repository**:
   Run the following command:
   ```bash
   git clone https://github.com/organization-name/computer-vision-lab.git
   cd computer-vision-lab
    ```

 2. **Install Dependencies:** Use the following command to install required libraries:
```bash
pip install -r requirements.txt
```

## Contributing

Contributions are welcome! Please follow these steps:

**Fork the repository.**
**Create a feature branch** (`git checkout -b feature-branch`).
**Commit changes** (`git commit -m 'Add new feature'`).
**Push to the branch** (`git push origin feature-branch`).
**Open a Pull Request.**


## License
```rust
This project is licensed under the MIT License - see the LICENSE file for details.
```
