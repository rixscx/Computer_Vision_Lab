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
Detects edges in the X and Y directions.
```
Output:
```
![image](https://github.com/user-attachments/assets/667bfabe-7e6a-484a-93bd-319ad5c05613)

2. Gaussian Blurring:
Reduces image noise with a Gaussian filter.
```
Output:
```
![image](https://github.com/user-attachments/assets/b8b36a5b-2a32-4804-a77f-39c10ad95c96)

3. Gabor Filtering:
Analyzes texture with directional Gabor filters.
```
Output:
```
![image](https://github.com/user-attachments/assets/3f1c6d58-493a-4f94-b5a7-cda6f69e4dbe)

4. Laplacian Edge Detection:
Applies Laplacian to highlight edges.
```
Output:
```
![image](https://github.com/user-attachments/assets/1158e76b-7ebb-4416-974d-a343de329306)

5. Fourier Transform:
Computes and displays the frequency spectrum.
```
Output:
```
![image](https://github.com/user-attachments/assets/546b6034-a240-4c8a-b68e-ddf9ab4e3d09)

6. Non-Maximum Suppression:
Suppresses non-maximum edges to refine results.
```
Output:
```
![image](https://github.com/user-attachments/assets/5fd07fc6-44c3-4674-beb6-a8a779632b5c)


7. Morphological Operations:
Performs operations such as dilation and erosion.
```
Output:
```
![image](https://github.com/user-attachments/assets/be3b79b4-df73-4795-af41-0caed3d7f2dc)

8. Bilateral Filtering:
Applies bilateral filtering for edge-preserving smoothing.
```
Output:
```
![image](https://github.com/user-attachments/assets/d263ad9b-2843-4baf-8623-cae80092184f)

9. Brightness Adjustment:
Adjusts the brightness of the image.
```
Output:
```
![image](https://github.com/user-attachments/assets/42bca985-f93d-4fc7-8702-b38ec1e40206)

10. Canny Edge Detection:
Detects edges using the Canny algorithm.
```
Output:
```
![image](https://github.com/user-attachments/assets/8619b30d-9c2f-4c53-92b9-8ba7c89e3fc8)

11. Emboss Filter:
Applies an emboss filter to the image.
```
Output:
```
![image](https://github.com/user-attachments/assets/f0233155-fdb7-49e6-9393-22b2e0f4e666)

12. Median Blur:
Applies median blur to the image.
```
Output:
```
![image](https://github.com/user-attachments/assets/3b727b52-9b91-4c60-af13-0009dd6fa18f)

13. Motion Blur:
Simulates motion blur on the image.
```
Output:
```
![image](https://github.com/user-attachments/assets/89b9ec54-0892-4d6b-85ab-3e23e0ba0538)

14. Sharpen Filter:
Sharpens the image.
```
Output:
```
![image](https://github.com/user-attachments/assets/3909b533-8f3c-4fc6-af4a-ece233163c03)

15. Add Gaussian Noise:
Adds Gaussian noise to the image.
```
Output:
```
![image](https://github.com/user-attachments/assets/15ef2a2c-6d53-4e44-b284-a8f45c46c7f7)

16. Grayscale Conversion:
Converts the image to grayscale.
```
Output:
```
![image](https://github.com/user-attachments/assets/bfa3d3c7-42ef-4386-b864-3d523d53f562)

17. Box Filter (Averaging Filter):
Applies a box filter for averaging.
```
Output:
```
![image](https://github.com/user-attachments/assets/828da229-0c3a-48c1-9cca-c8a4607c9c9e)

18. Unsharp Masking:
Enhances the image using unsharp masking.
```
Output:
```
![image](https://github.com/user-attachments/assets/598e37c3-c32d-4454-9bed-c6c20ff353c9)

19. Prewitt Filter:
Applies the Prewitt filter for edge detection.
```
Output:
```
![image](https://github.com/user-attachments/assets/19322a2d-6e94-4b74-be68-62ea4f660999)

20. Cartoon Effect:
Creates a cartoon effect on the image.
```
Output:
```
![image](https://github.com/user-attachments/assets/944e31e9-7e96-4594-941f-9e2e7f73fe9f)

22. Pencil Sketch Effect:
Converts the image to a pencil sketch.
```
Output:
```
![image](https://github.com/user-attachments/assets/19fb75b1-0f40-4e64-858f-293cae2ae05e)

22. Histogram Equalization:
Equalizes the histogram of the image.
```
Output:
```
![image](https://github.com/user-attachments/assets/73fc4220-965e-47f8-bbf3-d397f3a4ee6e)

23. CLAHE (Contrast Limited Adaptive Histogram Equalization):
Applies CLAHE for contrast enhancement.
```
Output:
```

![image](https://github.com/user-attachments/assets/2e619c28-1568-43d9-a025-582e001e2551)

24. Adaptive Thresholding:
Applies adaptive thresholding.
```
Output:
```

![image](https://github.com/user-attachments/assets/95e94733-a5fc-4781-9aee-d2568b4962dc)

25. Frequency Domain Filtering:
Applies high-pass and low-pass filters in the frequency domain.
```
Output:
```

![image](https://github.com/user-attachments/assets/24926afe-e354-4e48-a18b-87aea784da1c)

26. Bilateral Grid Filtering:
Applies bilateral grid filtering.
```
Output:
```

![image](https://github.com/user-attachments/assets/99f05b75-006d-4464-8ae3-b4c72cb451d0)

27. Edge-Preserving Filter:
Applies edge-preserving filtering.
```
Output:
```

![image](https://github.com/user-attachments/assets/8a932c66-09d7-4cd7-b80b-d93422eae3f1)

28. Scharr Filter:
Applies the Scharr filter for edge detection.
```
Output:
```

![image](https://github.com/user-attachments/assets/b9667ca1-405f-496a-b4f6-49b9b89e8573)

# **Project Structure**

```Code
Image_Preprosseing/
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

This project is licensed under the MIT License - see the LICENSE file for details.


## Acknowledgements

 - I would like to express my sincere gratitude to my lecturer, Dr. Agughasi Victor Ikechukwu (https://github.com/Victor-Ikechukwu), for their invaluable guidance and support throughout this project.
 - Their expertise and insights have been instrumental in the successful completion of this project on image clustering techniques using OpenCV and Matplotlib. I am deeply grateful for their encouragement and mentorship.
 - Thank you for providing the knowledge and resources needed to explore and implement various computer vision tasks.
