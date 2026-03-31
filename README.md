# Lung Image Classification using CNN

## Overview
This project implements a Convolutional Neural Network (CNN) to classify lung images into different categories. The model is trained from scratch and demonstrates the complete deep learning pipeline including preprocessing, training, and evaluation.

## Objective
To build a custom CNN model for image classification and understand the fundamentals of deep learning in medical imaging.

## Tools & Technologies
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## Workflow
1. Load dataset from directory
2. Preprocess images (resize, normalization)
3. Encode labels
4. Split dataset (train/test)
5. Train CNN model
6. Evaluate model performance

## Model Architecture
- Conv2D → MaxPooling
- Conv2D → MaxPooling
- Flatten → Dense → Output layer

## Results
The model was trained for 50 epochs and evaluated using accuracy and loss metrics. Training and validation curves were used to analyze performance.

## Repository Contents
- `lung_image_cnn.ipynb` — complete implementation

## Author
Kaniz Fatema Ankan
