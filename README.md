# 🚤Image Classification using Deep Learning

## Introduction
This project aims to build an automatic system to classify different types of boats using deep learning techniques. The goal is to reduce human error in misclassifying boat types by developing a bias-free and corruption-free system. The project involves creating a Convolutional Neural Network (CNN) and using transfer learning to build a lightweight model for deployment on mobile devices.

## Objective
- Develop a CNN model to classify boat images into 9 different categories.
- Build a lightweight model using transfer learning for mobile deployment.
- Compare the performance of both models.

## Dataset Description
The dataset contains images of 9 types of boats:
- Buoy
- Cruise_ship
- Ferry_boat
- Freight_boat
- Gondola
- Inflatable_boat
- Kayak
- Paper_boat
- Sailboat

The dataset consists of a total of 1162 images, organized into directories corresponding to each class.

## Steps and Tasks Performed
### 1. Data Preparation
- Load and preprocess the dataset.
- Split the data into training and testing sets.

### 2. Build and Train a CNN Model
- Construct a CNN architecture for boat classification.
- Compile the model using Adam optimizer, categorical_crossentropy loss, and metrics such as accuracy, precision, and recall.
- Train the model on the training data.
- Evaluate the model on the test data.
- Plot the confusion matrix and generate a classification report.

### 3. Transfer Learning for Lightweight Model
- Use a pre-trained MobileNetV2 model as the base.
- Add custom layers on top of MobileNetV2 for classification.
- Compile the model with similar metrics as the CNN model.
- Implement early stopping during training.

### 4. Comparison and Evaluation
- Compare the performance of the CNN model and the MobileNetV2-based model.
