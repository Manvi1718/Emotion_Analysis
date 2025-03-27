# Comparative Analysis of Deep Learning Models for Facial Emotion Recognition

## Overview

Facial Emotion Recognition (FER) is a technique that analyzes and examines facial expressions to identify human emotions. It is widely used to study behavioral patterns, and deep learning has revolutionized its performance. This project implements three deep learning models—ResNet50, EfficientNet, and VGG16—using transfer learning for emotion classification. A comparative analysis has been conducted based on various performance metrics, including accuracy, precision, recall, and F1-score. The project covers data preprocessing, model training, evaluation, and visualization of results.

## Features

- Utilizes ResNet50, EfficientNet, and VGG16 models for robust emotion classification.
- Implements custom transformations and data augmentation to improve accuracy.
- Trains models on the CK+ dataset, classifying images into seven distinct emotions.
- Provides visualizations of predictions, loss curves, and model performance.

## Dataset

The dataset used in this project is the **Cohn-Kanade Extended (CK+) dataset**, which contains images of human faces showing different facial expressions. The dataset consists of facial expressions labeled into seven categories:

- Anger
- Contempt
- Disgust
- Fear
- Happiness
- Sadness
- Surprise

The dataset is preprocessed and stored in Google Drive for efficient access and training in Google Colab.

## Models
- EffcientNet
- ResNet50
- VGG16

## Results

From the experimental study conducted on the CK+ dataset, EfficientNet has demonstrated superior performance compared to the other models. The results are summarized as follows:

| Model Name   | Model Accuracy (%) | Accuracy | Precision | Recall | F1 Score |
|-------------|-------------------|----------|-----------|--------|----------|
| EfficientNet | 98.31             | 0.366935 | 0.403429  | 0.366935 | 0.359769 |
| VGG         | 82.42             | 0.193548 | 0.202163  | 0.193548 | 0.180351 |
| ResNet      | 91.15             | 0.298387 | 0.331755  | 0.298387 | 0.297495 |

<img src="https://github.com/user-attachments/assets/c07b3277-4510-45d9-a4eb-f6eff4931326" width="600" height="600">

<img src="https://github.com/user-attachments/assets/392c405f-cac6-478e-ab1b-70be65bfe586" width="650" height="400">

<img src="https://github.com/user-attachments/assets/2bf702c6-a4e0-4f35-b9ac-69cf02dca5e9" width="650" height="400">
