# Industrial Surface Crack Detection using CNN

## Overview

This project is a Deep Learning-based Industrial Surface Crack Detection System developed using Convolutional Neural Networks (CNN). The system automatically detects cracks on industrial surfaces using image classification techniques.

The model is trained on positive (crack) and negative (non-crack) image datasets and can classify unseen surface images as:

* Crack Detected
* No Crack

---

## Features

* Automated crack detection using CNN
* Image preprocessing and augmentation
* Train, validation, and test dataset splitting
* Real-time single image prediction
* Confusion matrix and classification report
* Accuracy and loss visualization graphs
* Model checkpoint saving and early stopping

---

## Technologies Used

### Programming Language

* Python

### Deep Learning Framework

* TensorFlow
* Keras

### Libraries

* NumPy
* Matplotlib
* Scikit-learn

### Image Processing

* TensorFlow ImageDataGenerator

---

## Project Structure

```bash
CNN_Surface_Crack_Detection/
│
├── CrackDataset/
│   ├── Positive/
│   └── Negative/
│
├── Processed_CrackDataset/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── Best_Crack_Detection_Model.keras
├── Final_Marvellous_Crack_Detection_Model.keras
├── Crack_Detection.py
├── requirements.txt
└── README.md
```

---

## CNN Architecture

The CNN model contains:

* Convolution Layers
* Batch Normalization
* MaxPooling Layers
* Dropout Layers
* Fully Connected Dense Layers
* Sigmoid Output Layer

---

## Dataset Processing

The dataset is automatically divided into:

* 70% Training Data
* 15% Validation Data
* 15% Testing Data

Data augmentation techniques used:

* Rotation
* Zoom
* Width Shift
* Height Shift
* Horizontal Flip

---

## Model Training

The model uses:

* Adam Optimizer
* Binary Crossentropy Loss
* EarlyStopping
* ModelCheckpoint
* ReduceLROnPlateau

---

## Performance Evaluation

The project evaluates model performance using:

* Test Accuracy
* Test Loss
* Confusion Matrix
* Classification Report

---

## Single Image Prediction

The system supports prediction on a single unseen image and displays:

* Prediction Score
* Crack/No Crack Result
* Output Visualization

---

## How to Run the Project

### Step 1: Clone Repository

```bash
git clone https://github.com/theankita/Surface_Crack_Detection.git
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Run Project

```bash
python Crack_Detection.py
```

---

## Future Improvements

* Real-time crack detection using webcam
* Mobile deployment
* Transfer Learning using ResNet/EfficientNet
* Crack localization using Object Detection

---

## Author

Ankita Shinde

GitHub:
https://github.com/theankita

