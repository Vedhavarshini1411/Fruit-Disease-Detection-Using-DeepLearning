# Fruit Disease Detection Using Deep Learning

## Overview
This project focuses on automatic fruit disease detection using **Deep Learning** and **Digital Image Processing** techniques in MATLAB.  
A pretrained **ResNet-50 Convolutional Neural Network (CNN)** model is used with **Transfer Learning** to classify healthy and diseased fruits from images.

The system processes fruit images, extracts important visual features automatically, and predicts the disease category with high accuracy.

---

## Features
- Fruit disease classification using Deep Learning
- Transfer Learning with ResNet-50
- Automatic feature extraction using CNN
- Data augmentation for improved accuracy
- Multi-class image classification
- Real-time prediction support
- MATLAB implementation

---

## Technologies Used
- MATLAB
- Deep Learning Toolbox
- Image Processing Toolbox
- ResNet-50 Pretrained Network
- Digital Image Processing
- Convolutional Neural Networks (CNN)

---

## Project Workflow

```text
Dataset Images
       ↓
Image Preprocessing
       ↓
Data Augmentation
       ↓
ResNet-50 Transfer Learning
       ↓
Model Training
       ↓
Disease Classification
       ↓
Prediction Results
```

---

## Dataset
The dataset contains images of healthy and diseased fruits organized into folders based on disease categories.

Example:

```text
Dataset/
│
├── Apple_Healthy/
├── Apple_Scab/
├── Black_Rot/
└── ...
```

---

## Files Included

```text
Fruit-Disease-Detection-Using-DeepLearning/
│
├── MATLAB_Code/
│   └── fruit_disease_detection.m
│
├── Dataset/
│   └── Dataset_Samples
│
├── Results/
│   ├── Accuracy Graph
│   ├── Test_Images
│   └── Prediction Results
│
└── README.md
```

---

## Methodology

### 1. Dataset Loading
Images are loaded using MATLAB `imageDatastore`.

### 2. Data Splitting
Dataset is divided into:
- 80% Training Data
- 20% Testing Data

### 3. Image Preprocessing
Images are resized according to ResNet-50 input size.

### 4. Data Augmentation
Random transformations like:
- Rotation
- Translation
- Shifting

are applied to improve model generalization.

### 5. Transfer Learning
The pretrained ResNet-50 model is modified by replacing the final classification layers according to the number of fruit disease classes.

### 6. Model Training
The network is trained using:
- Adam Optimizer
- Mini-batch training
- Learning rate optimization

### 7. Prediction
The trained model predicts diseases from unseen fruit images.

---

## Results
- High classification accuracy achieved using Transfer Learning
- Improved robustness due to data augmentation
- Successful detection of multiple fruit diseases

Example outputs are available in the `Results` folder.

---

## Applications
- Smart Agriculture
- Automated Fruit Quality Inspection
- Disease Monitoring Systems
- AI-based Farming Solutions
- Real-time Fruit Disease Detection

---

## Future Improvements
- Real-time webcam-based detection
- Mobile application deployment
- IoT integration
- Raspberry Pi implementation
- YOLO-based object detection

---

## Novelty of the Project
- Uses Transfer Learning with ResNet-50
- Automatic feature extraction without manual image processing
- Improved accuracy using data augmentation
- Real-time disease prediction capability
- Efficient classification using small datasets

---

## How to Run

1. Open MATLAB
2. Load the project folder
3. Open the MATLAB code file
4. Set dataset path correctly
5. Run the script

```matlab
run('fruit_disease_detection.m')
```

---

## Output
The model predicts the disease category of the fruit image and displays the result.

Example:

```text
Detected Disease: Apple Scab
Accuracy: 93.33%
```

---

## Author
Vedhavarshini N  
Tharini P

Electronics and Communication Engineering  
Easwari Engineering College, Chennai

---

## License
This project is for educational and research purposes.
