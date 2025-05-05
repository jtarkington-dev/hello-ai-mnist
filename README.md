# Hello AI: MNIST Digit Classifier

A beginner-friendly PyTorch project that trains a simple neural network to recognize handwritten digits using the MNIST dataset.  
This project is part of my AI portfolio to demonstrate hands-on model training, evaluation, and visualization.

## Features
- PyTorch neural network from scratch
- Live accuracy tracking
- Matplotlib visualizations
- Jupyter Notebook for full walkthrough

## Results Summary

Achieved **97.77% test accuracy** using a 3-layer fully connected neural network trained on the MNIST dataset.

**Model Architecture:**
- Input: 784 nodes (28×28 image flattened)
- Hidden Layers: 128 → 64 neurons (ReLU activation)
- Output: 10 classes (digits 0–9) with log-softmax

**Training Info:**
- Epochs: 5
- Batch Size: 64
- Optimizer: Adam
- Loss: Negative Log Likelihood Loss

