# Implementation of a Feedforward Neural Network (FNN) for MNIST Digit Classification

## Overview
This project implements a Feedforward Neural Network (FNN) for digit classification using the MNIST dataset. The model is built using TensorFlow/Keras and optimized with various hyperparameters.

## Dataset
- **Name:** MNIST  
- **Images:** 60,000 training, 10,000 test  
- **Size:** 28x28 pixels (grayscale)  
- **Classes:** 10 (digits 0-9)  

## Model Architecture
- **Input:** 784 neurons (flattened 28x28 image)  
- **Hidden Layers:** 3 layers, 128 neurons each (ReLU activation)  
- **Output Layer:** 10 neurons (Softmax activation)  
- **Optimizers:** Adam, SGD, RMSprop  
- **Loss Functions:** Cross-Entropy Loss, Squared Error Loss  

## Installation
Ensure you have Python 3.x installed, then install the dependencies:

```bash
pip install tensorflow numpy matplotlib scikit-learn# Emnist-dataset
