# Face Mask Detection using Deep Learning

## Overview

This project implements a Convolutional Neural Network (CNN) for automatic face mask detection. The model classifies facial images into two categories:

* With Mask
* Without Mask

The system can be used for automated mask compliance monitoring in public places, workplaces, healthcare facilities, and transportation systems.

---

## Problem Statement

During public health emergencies, monitoring mask usage becomes important for reducing disease transmission. Manual monitoring is inefficient and time-consuming.

This project aims to develop a Deep Learning-based solution capable of automatically detecting whether a person is wearing a face mask using image classification techniques.

---

## Dataset

The dataset consists of two classes:

1. With Mask
2. Without Mask

Dataset Structure:

```
data/
│
├── with_mask/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
│
├── without_mask/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
```

---

## Project Workflow

1. Data Collection
2. Image Preprocessing
3. Image Resizing (150 × 150)
4. Dataset Preparation
5. CNN Model Development
6. Model Training
7. Model Evaluation
8. Face Mask Prediction

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Scikit-Image
* Scikit-Learn

---

## Model Architecture

The CNN architecture consists of:

* Convolution Layer (Conv2D)
* Max Pooling Layer
* Flatten Layer
* Dense Hidden Layers
* Softmax Output Layer

### Input Shape

```
150 × 150 × 1
```

### Output Classes

* With Mask
* Without Mask

---

## Features

* Binary Image Classification
* Deep Learning-Based Prediction
* Automatic Face Mask Detection
* Lightweight CNN Architecture
* Easy Integration with Webcam Applications

---

## Training Process

* Dataset split into Training and Testing sets
* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Metric: Accuracy
* Epochs: 10

---

## Prediction

The trained model can predict whether a person is wearing a face mask from an input image.

Example Output:

```
With Mask
```

or

```
Without Mask
```

---

## Applications

* Public Safety Monitoring
* Smart Surveillance Systems
* Healthcare Facilities
* Airports and Railway Stations
* Educational Institutions
* Workplace Safety Monitoring

---

## Future Improvements

* Real-Time Webcam Detection
* Face Detection Integration using OpenCV
* Transfer Learning using MobileNetV2
* Improved Accuracy with Data Augmentation
* Deployment using Streamlit
* Edge Device Deployment using Raspberry Pi

---

## Results

The CNN model successfully learns facial mask patterns and can classify images into mask and no-mask categories, demonstrating the effectiveness of Deep Learning in image-based safety monitoring applications.

---

## Author

Ashik Kumar

B.Tech Electronics and Communication Engineering (ECE)

Machine Learning & Computer Vision Enthusiast
