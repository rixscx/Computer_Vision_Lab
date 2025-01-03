# Image_Preprocessing.ipynb

## Image Processing Techniques: Edge Detection and Frequency Analysis

# Original Image:
![M_U](https://github.com/user-attachments/assets/ca6c9967-b3f8-43d3-af02-f3caaf7a1c65)

## 🚀 Overview
This notebook covers several computer vision tasks using OpenCV and Matplotlib. Here are some key operations included in the notebook:
- Sobel Edge Detection
- Gaussian Blurring
- Gabor Filtering
- Laplacian Edge Detection
- Fourier Transform
- And more...

> **Goal:** To visualize and explore different ways of identifying edges and frequency components in images.

# Computer Vision Lab - Edge Detection and Filtering Techniques

This repository provides a Jupyter Notebook showcasing various computer vision techniques using OpenCV and Python. The notebook demonstrates edge detection, image filtering, and texture analysis on grayscale images.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

## **Features**

1. **Sobel Edge Detection**: Detects edges in X and Y directions.
2. **Gaussian Blurring**: Reduces image noise with a Gaussian filter.
3. **Gabor Filtering**: Analyzes texture with directional Gabor filters.
4. **Laplacian Edge Detection**: Applies Laplacian to highlight edges.
5. **Fourier Transform**: Computes and displays the frequency spectrum.
6. **Non-Maximum Suppression**: Suppresses non-maximum edges to refine results.
7. **Morphological Operations**: Performs operations such as dilation and erosion.
8. **Bilateral Filtering**: Applies bilateral filtering for edge-preserving smoothing.
9. **Brightness Adjustment**: Adjusts the brightness of the image.
10. **Canny Edge Detection**: Detects edges using the Canny algorithm.
11. **Emboss Filter**: Applies an emboss filter to the image.
12. **Median Blur**: Applies median blur to the image.
13. **Motion Blur**: Simulates motion blur on the image.
14. **Sharpen Filter**: Sharpens the image.
15. **Add Gaussian Noise**: Adds Gaussian noise to the image.
16. **Grayscale Conversion**: Converts the image to grayscale.
17. **Box Filter (Averaging Filter)**: Applies a box filter for averaging.
18. **Unsharp Masking**: Enhances the image using unsharp masking.
19. **Prewitt Filter**: Applies the Prewitt filter for edge detection.
20. **Cartoon Effect**: Creates a cartoon effect on the image.
21. **Pencil Sketch Effect**: Converts the image to a pencil sketch.
22. **Histogram Equalization**: Equalizes the histogram of the image.
23. **CLAHE (Contrast Limited Adaptive Histogram Equalization)**: Applies CLAHE for contrast enhancement.
24. **Adaptive Thresholding**: Applies adaptive thresholding.
25. **Frequency Domain Filtering**: Applies high-pass and low-pass filters in the frequency domain.
26. **Bilateral Grid Filtering**: Applies bilateral grid filtering.
27. **Edge-Preserving Filter**: Applies edge-preserving filtering.
28. **Scharr Filter**: Applies the Scharr filter for edge detection.

## **Installation**

1. **Clone the repository**:
   Run the following command:
   ```bash
   git clone https://github.com/rixscx/Computer_Vision_Lab.git
   cd Computer_Vision_Lab
   ```

2. **Install Dependencies**:
   Use the following command to install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## **Usage**

Open the Jupyter Notebook: Start Jupyter Notebook and open `Image_Preprosseing.ipynb`:

```bash
jupyter notebook 
```

# **Image_Preprosseing.ipynb**

1. Sobel Edge Detection: 
Displays the original image alongside edges detected in the X and Y directions and their combination.

2. Gaussian Blurring:
Shows the effect of Gaussian blurring on a grayscale image.

3. Gabor Filtering:
Visualizes texture analysis at multiple orientations.

4. Laplacian Edge Detection:
Highlights edges using the Laplacian operator.

5. Fourier Transform:
Computes and displays the magnitude spectrum.

6. Non-Maximum Suppression:
Refines Sobel edge detection results by suppressing non-maximum values.

7. Cartoon Effect:
Applies cartoon effect to the image, making it look like a cartoon.

8. Pencil Sketch Effect:
Transforms the image into a pencil sketch.

9. Histogram Equalization:
Improves the contrast of the image using histogram equalization.

10. CLAHE (Contrast Limited Adaptive Histogram Equalization):
Enhances the image contrast more effectively than standard histogram equalization.

# **Project Structure**

```Code
computer-vision-lab/
│
├── Image_Preprosseing.ipynb  # Jupyter Notebook with all image processing techniques
├── requirements.txt          # List of dependencies
└── README.md                 # Project documentation
```
# **Contributing**
**Contributions are welcome! Please follow these steps:**

1. .Fork the repository.
2. Create a feature branch (git checkout -b feature-branch).
3. Commit changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.

# **License**
This project is licensed under the MIT License - see the LICENSE file for details.

# **References**

***OpenCV Documentation:***
```
https://docs.opencv.org/
```
***Matplotlib Documentation:***
```
https://matplotlib.org/stable/contents.html
```
***Scikit-Image Documentation:***
```
https://scikit-image.org/docs/stable/
```


## License

[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgments

I would like to express my sincere gratitude to my lecturer, Dr. Agughasi Victor Ikechukwu(https://github.com/Victor-Ikechukwu), for their invaluable guidance and support throughout this project. 

Their expertise and insights have been instrumental in the successful completion of this project on image processing techniques using OpenCV and Matplotlib. I am deeply grateful for their encouragement and mentorship.

Thank you for providing the knowledge and resources needed to explore and implement various computer vision tasks.