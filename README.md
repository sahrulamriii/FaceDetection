# Face Detection and Background Removal using OpenCV and MTCNN

This project implements a robust pipeline for **Face Detection** and **Background Removal** using two powerful methods: **OpenCV** (Haar Cascade) and **MTCNN** (Multi-task Cascaded Convolutional Networks). It demonstrates the strengths of MTCNN in detecting faces with high accuracy under challenging conditions, as well as the limitations of OpenCV-based methods. The results highlight the suitability of MTCNN for complex scenarios like non-frontal poses and uneven lighting, followed by background removal using advanced segmentation techniques.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Contributors](#contributors)

---

## Overview
The goal of this project is to compare the performance of **OpenCV** and **MTCNN** for face detection, and to demonstrate background removal capabilities. While OpenCV provides a lightweight solution, MTCNN excels in handling complex images, making it ideal for high-accuracy applications. 

### Workflow:
1. Detect faces using **OpenCV (Haar Cascade)** and **MTCNN**.
2. Extract the detected faces and focus on these regions for further processing.
3. Remove the background using segmentation (e.g., U-Net or custom methods).
4. Visualize and compare the results.

---

## Features
- Face detection using:
  - **OpenCV** for lightweight processing.
  - **MTCNN** for accurate and robust detection under complex conditions.
- Background removal for detected faces using segmentation models.
- Comparison of results between OpenCV and MTCNN.
- Support for multiple images and batch processing.

---

## Technologies Used
- **Python 3.8+**
- **OpenCV** for traditional face detection.
- **MTCNN** for deep learning-based face detection.
- **NumPy** and **Matplotlib** for data processing and visualization.
- **TensorFlow/Keras** for advanced segmentation models.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/face-detection-mtcnn-opencv.git
   cd face-detection-mtcnn-opencv


2. Create a virtual environment and install dependencies:
   ```python
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
3. Download any additional pre-trained models (if required) as specified in the code.

# Usage
Running the Script
Place your input images in the input_images/ folder.
Run the detection and background removal script:
```bash
python face_detection.py
```
Processed images with detected faces and removed backgrounds will be saved in the output_images/ folder.

# Results

# Future Improvements
- Enhance background removal using state-of-the-art segmentation models like U-Net or DeepLabV3+.
- Optimize processing time for large datasets or real-time applications.
- Extend the pipeline to detect multiple faces and process them individually.
- Integrate with a web-based interface for user-friendly operation.

# Acknowledgments
Thanks to the creators of OpenCV and MTCNN for providing the tools used in this project. This work was inspired by the need to develop efficient, high-accuracy face detection and background removal methods.

# Feedback
Feel free to open an issue or submit a pull request for improvements. We appreciate your feedback!

# Contributors
- Sahrul Amri - Project Development 
- M. Alghorizmi M.
- M. Ivan Khoirur Rizky
- Akfi Rozada

## Special thanks to open-source libraries and pre-trained models used in this project.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
