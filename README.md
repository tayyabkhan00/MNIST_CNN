# Handwritten Digit Classification using CNN (PyTorch)

## Overview
This project implements a Convolutional Neural Network (CNN) using PyTorch to classify handwritten digits (0–9) from the MNIST dataset. The model automatically extracts spatial features from images and achieves high classification accuracy.

## Dataset
- MNIST Handwritten Digit Dataset
- 60,000 training images
- 10,000 test images
- Image size: 28x28 grayscale

## Technologies Used
- Python
- PyTorch
- TorchVision
- NumPy
- Matplotlib

## Model Architecture
- Convolutional Layers with ReLU activation
- Max Pooling layers for spatial reduction
- Fully Connected layers for classification
- Softmax output layer

## Training
- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Epochs: 5
- Batch Size: 64

## Results
- Test Accuracy: ~99%

## Conclusion
The CNN effectively learns hierarchical image features and accurately classifies handwritten digits, demonstrating the power of deep learning in computer vision tasks.
