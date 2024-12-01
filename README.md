# Brain Tumor Binary Classification using Convolutional Neural Networks

## Project Overview

This project aims to classify brain MRI scans into two categories: "No Tumor" and "Pituitary Tumor" using Convolutional Neural Networks (CNNs). The project utilizes a dataset of brain MRI images and leverages the power of deep learning for accurate classification.

## Features

- **Binary Classification:** The project focuses on distinguishing between two classes of brain scans - No Tumor and Pituitary Tumor.
- **Convolutional Neural Networks:** Employs CNNs, a powerful deep learning architecture, for image classification.
- **Data Augmentation:** Augments the training data to enhance model robustness and prevent overfitting.
- **Model Evaluation:** Evaluates the trained model using accuracy and confusion matrix metrics.

## Dataset

The project utilizes a brain MRI dataset from Kaggle, specifically focusing on two classes: No Tumor and Pituitary Tumor. The dataset is split into training and testing sets.

## Model

A Convolutional Neural Network (CNN) is implemented for classification. The model architecture consists of convolutional layers, max pooling layers, dropout layers, and fully connected layers.

## Results

The model achieves high accuracy on both the training and testing sets:

- **Training Accuracy:** 91.64%
- **Testing Accuracy:** 96.17%

## Usage

1. **Data Loading:** Load the brain MRI dataset.
2. **Data Preprocessing:** Resize, normalize, and augment the images.
3. **Model Training:** Train the CNN model on the training data.
4. **Model Evaluation:** Evaluate the model's performance on the testing data.
5. **Confusion Matrix:** Visualize the model's performance using a confusion matrix.

## Conclusion

The project demonstrates the effectiveness of Convolutional Neural Networks for brain tumor binary classification. The high accuracy achieved on both training and testing sets highlights the model's potential for real-world applications.
