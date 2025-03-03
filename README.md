# EMNIST Classification using Feedforward Neural Network (FNN)

## Overview
This project trains a **Feedforward Neural Network (FNN)** on the **EMNIST dataset** for handwritten character classification. The model is implemented in **PyTorch** and optimized using various optimizers and activation functions.

## Dataset
- **Name:** EMNIST (Extended MNIST)
- **Images:** Handwritten letters and digits
- **Size:** 28x28 pixels (grayscale)
- **Classes:** 26 letters (A-Z) and digits (0-9) (depending on the subset used)

## Model Architecture
- **Input Layer:** 784 neurons (flattened 28x28 image)
- **Hidden Layers:** Configurable, tested with different depths
- **Activation Functions:** ReLU, Sigmoid
- **Output Layer:** Number of neurons based on dataset class count
- **Optimizers:** Adam, SGD, RMSProp, MGD, NGD
- **Regularization:** L2 Regularization
- **Evaluation Metrics:** Accuracy, Confusion Matrix, Classification Report

## Installation
Ensure you have Python 3.x installed, then install the required dependencies:

```bash
pip install torch torchvision numpy matplotlib scikit-learn emnist deeplake
