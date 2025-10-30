🧠 Image Processing Basics

This project explores the fundamentals of *image processing* using *Python, **OpenCV, and **NumPy*.  
It includes operations like image loading, resizing, color conversions, edge detection, and basic transformations.


🎯 Objective
To understand how images are represented and manipulated using Python libraries and to practice common image processing operations.


⚙ Technologies Used
- *Python*
- *OpenCV (cv2)*
- *NumPy*
- *Matplotlib*


📁 Project Files
| File | Description |
|------|--------------|
| image processing.ipynb | Jupyter Notebook containing all image processing code and explanations |
| (Optional) sample_image.jpg | Example image used for processing |


🔍 Topics Covered
- Reading and displaying images using OpenCV  
- Image resizing, cropping, and rotation  
- Color space conversion (RGB ↔ Gray ↔ HSV)  
- Applying filters (blur, Gaussian, median)  
- Edge detection (Canny, Sobel)  
- Drawing shapes and text on images  
- Combining and masking images


📸 Sample Outputs
(Add screenshots of your output images here)
    ![Original Image](original.png)
    ![Gray Image](gray.png)
    ![Edge Detection](edges.png)

🧠 Learnings
- Understanding image pixel data as NumPy arrays
- Using OpenCV functions for transformation and filtering
- Visualizing processed images using Matplotlib
- Building foundation for computer vision and deep learning


🔮 Future Improvements
- Add histogram equalization and thresholding examples
- Experiment with face detection (Haar Cascades)
- Convert notebook into an interactive Streamlit or Gradio app



🧩 Example Code
```python
import cv2
import matplotlib.pyplot as plt

# Read image
img = cv2.imread('sample_image.jpg')

# Convert to grayscale
gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)

# Display
plt.imshow(gray, cmap='gray')
plt.title('Grayscale Image')
plt.show()







