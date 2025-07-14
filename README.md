# PyTorch MNIST Classifier

A simple fully connected neural network for MNIST digit classification using PyTorch.

## Features
- 2-layer fully connected network
- MNIST dataset training and testing
- GPU support with CUDA

## Requirements
pip install -r requirements.txt

## Usage
python mnist_classifier.py

## Model Architecture
- Input layer: 784 neurons (28x28 flattened images)
- Hidden layer: 50 neurons with ReLU activation
- Output layer: 10 neurons (digit classes)