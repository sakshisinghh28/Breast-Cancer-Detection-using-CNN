# Breast Cancer Detection using Convolutional Neural Networks (CNNs)

## Overview
This project aims to develop a CNN-based model for breast cancer detection using mammography images from the MIAS dataset.

## Dataset
- **MIAS Dataset**: Contains labeled mammography images.
- **Preprocessing**: Images were resized to `224x224` pixels and normalized.

## Model Architecture
- Implemented a sequential CNN model with convolutional and pooling layers.
- Added fully connected layers for classification with dropout regularization.

## Training and Evaluation
- Split dataset into training and test sets.
- Utilized EarlyStopping and ModelCheckpoint callbacks during training.

## Results
- The model shows promising performance in distinguishing between benign and malignant cases.

## Conclusion
This project demonstrates the application of CNNs in medical image analysis, specifically for breast cancer detection.

---

