# PCOS Detection Using Machine Learning

## Overview
This project aims to develop an intelligent system for detecting **Polycystic Ovary Syndrome (PCOS)** using machine learning techniques. The system analyzes ultrasound images of ovaries to detect the presence of ovarian cysts. A **Convolutional Neural Network (CNN)** is used for feature extraction from ultrasound images, and an **ensemble learning model** classifies whether the ovary is affected by PCOS.

PCOS is a hormonal disorder common among women of reproductive age, and early detection is crucial for managing its symptoms and complications.

## Features
- **Convolutional Neural Network (CNN)** for automated feature extraction.
- **Transfer Learning** for improved model performance.
- **Ensemble Learning** with base learners (e.g., Random Forest, SVM) and boosting/bagging for final classification.
- **Graphical User Interface (GUI)** for easy use, built with Tkinter, allowing users to upload images and receive PCOS predictions.
- High **accuracy** of up to **99.9%** based on the dataset.


## Installation

### Prerequisites
- **Python 3.x**
- **TensorFlow/Keras** for building the CNN.
- **OpenCV** for image processing.
- **Pillow** for handling images in Tkinter.
- **NumPy** for numerical operations.


# Usage
# GUI: 
The graphical interface allows users to upload ultrasound images and view predictions on whether PCOS is detected.

# Model Performance
The CNN model achieved an accuracy of 99.9% on the training set and 96-99% on various test datasets of ultrasound images. This high accuracy makes it a reliable tool for diagnosing PCOS.

# Future Enhancements
Integrate additional imaging techniques such as MRI or CT scans to improve diagnostic accuracy.
Develop a web-based or mobile app for broader accessibility.
Implement real-time monitoring using telemedicine platforms.
