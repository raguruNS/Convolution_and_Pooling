# Project 12: Understanding Convolution and Pooling

## 📌 Project Overview
This project demonstrates how convolution and pooling operations work in Convolutional Neural Networks (CNNs). Using Python and OpenCV, different convolution filters are applied to an image to extract features, detect edges, sharpen details, and reduce noise. Max pooling and average pooling are used to reduce the spatial dimensions of the image.

## 🎯 Objectives
- Understand the concept of convolution in image processing.
- Apply different convolution filters to images.
- Perform max pooling and average pooling.
- Visualize and compare the original image and processed feature maps.
- Understand how convolution and pooling are used in CNNs.

## 🛠️ Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

## 📂 Project Structure

```text
Project-12-Convolution-and-Pooling/
│
├── Project_12_Convolution_and_Pooling.ipynb
└── README.md
```

## ⚙️ Installation

Install the required libraries:

```python
!pip install opencv-python matplotlib numpy
```

The notebook includes a separate installation cell, so you can also run the project directly in Google Colab.

## 🚀 How to Run the Project

1. Download or clone the project repository.
2. Open `Project_12_Convolution_and_Pooling.ipynb` in Google Colab.
3. Execute the notebook cells in order.
4. Upload a sample image when prompted.
5. View the original image, convolution outputs, and pooling results.
6. Compare the output images to understand the effects of each operation.

## 🔍 Project Tasks

### Task 1: Load a Sample Image
- Upload an image using Google Colab.
- Resize the image to 256 × 256 pixels.
- Convert the image to grayscale for processing.

### Task 2: Apply Convolution and Pooling
**Convolution filters:**
- Edge detection: highlights boundaries and changes in intensity.
- Sharpening: enhances image details.
- Blurring: smooths the image.

**Pooling operations:**
- Max pooling: selects the maximum pixel value from each 2 × 2 region.
- Average pooling: calculates the average pixel value from each 2 × 2 region.

### Task 3: Visualize and Compare Results
- Display the original and grayscale images.
- Visualize the convolution filter outputs.
- Compare max pooling and average pooling results.
- Observe how pooling reduces image dimensions.

## 📊 Expected Output
The project produces visual comparisons of:
- Original image
- Grayscale image
- Edge detection feature map
- Sharpened image
- Blurred image
- Max pooling output
- Average pooling output

Pooling reduces the image dimensions from 256 × 256 to 128 × 128 pixels.

## 🧠 Concepts Learned
- Image preprocessing
- Convolution kernels and filters
- Edge detection
- Image sharpening and blurring
- Max pooling
- Average pooling
- Feature extraction in CNNs
- Spatial dimension reduction

## 🏁 Conclusion
This project demonstrates how convolution filters extract useful visual information from images and how pooling operations reduce spatial dimensions. These techniques form important components of CNN architectures used in image classification, object detection, facial recognition, and other computer vision applications.

## 👨‍💻 Author
**Name:** Nitheesh

**Project:** Project 12 – Understanding Convolution and Pooling
