Breast Cancer Detection using Convolutional Neural Networks (CNNs)
Overview
This project focuses on developing a CNN-based model to detect breast cancer from mammography images. The goal is to leverage deep learning techniques to assist in early and accurate diagnosis.

Dataset
MIAS Dataset: Used the Mammographic Image Analysis Society (MIAS) dataset, containing labeled mammography images.
Preprocessing: Images were resized to 224x224 pixels and normalized for input into the CNN model.
Model Architecture
CNN Architecture: Implemented a sequential CNN model with several convolutional layers followed by max-pooling layers for feature extraction and down-sampling.
Fully Connected Layers: Added dense layers for classification, with dropout regularization to prevent overfitting.
Activation and Loss: Used ReLU activation for hidden layers and sigmoid activation for binary classification. Optimized using binary cross-entropy loss.
Training
Data Splitting: Split dataset into training and test sets (80/20 ratio).
Callbacks: Incorporated EarlyStopping and ModelCheckpoint callbacks to monitor validation loss and save the best model during training.
GPU Acceleration: Utilized Google Colab with T4 GPU for faster computation.
Evaluation
Performance Metrics: Evaluated model performance on the test set using accuracy and loss metrics.
Visualization: Plotted training and validation curves for loss and accuracy to analyze model performance over epochs.
Results
Achieved a test accuracy of XX% on the breast cancer detection task.
Model shows promising performance in distinguishing between benign and malignant cases.

Conclusion
This project demonstrates the application of CNNs in medical image analysis, specifically for breast cancer detection. The developed model shows potential for aiding radiologists in diagnosing breast cancer accurately and early.
