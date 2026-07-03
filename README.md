# MNIST Handwritten Digit Classifier using PyTorch

## Overview

This project implements a feedforward neural network (Multi-Layer Perceptron) using PyTorch to classify handwritten digits from the MNIST dataset. It demonstrates the complete deep learning workflow, including data preprocessing, model training, evaluation, visualization, and model persistence.

## Features

- Load and preprocess the MNIST dataset
- Build a neural network using PyTorch
- Train the model using the Adam optimizer
- Evaluate model performance using accuracy
- Visualize training loss
- Save and load trained model weights
- Predict handwritten digits

## Tech Stack

- Python
- PyTorch
- Torchvision
- Matplotlib

## Dataset

- MNIST Handwritten Digits
- 60,000 training images
- 10,000 test images
- Image size: 28 × 28 pixels
- 10 output classes (0–9)

## Model Architecture

Input (784)

↓

Linear (784 → 128)

↓

ReLU

↓

Linear (128 → 10)

## Results

The model is trained on the MNIST dataset and evaluated using classification accuracy on the test set.


## Future Improvements

- Add validation accuracy and loss curves
- Confusion matrix
- GPU training support
- CNN-based implementation
- Hyperparameter tuning

## Author

Hitesha Kalwar
