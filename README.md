# Hello AI: MNIST Digit Classifier

A beginner-friendly PyTorch project that trains a simple neural network to recognize handwritten digits using the MNIST dataset.  
This project is part of my AI portfolio to demonstrate hands-on model training, evaluation, and visualization.

## Features

- Fully connected neural network built with PyTorch  
- Clean Jupyter Notebook walkthrough  
- Live accuracy tracking during training  
- Visualization of predictions, misclassifications, and confusion matrix  
- Model saving and reloading support  

## Model Summary

**Architecture**  
- Input: 784 nodes (28×28 grayscale images flattened)  
- Hidden Layers: 128 → 64 neurons (ReLU activation)  
- Output: 10 classes (digits 0–9, using log-softmax)  

**Training Configuration**  
- Dataset: MNIST  
- Epochs: 5  
- Batch Size: 64  
- Optimizer: Adam  
- Loss Function: Negative Log Likelihood Loss  
- Test Accuracy: **97.77%**

## Evaluation

- **Confusion Matrix** and **misclassified digits** are displayed for insight into performance.
- Model predictions are visualized alongside ground truth labels.

## Save and Reload

The trained model is saved to `mnist_model.pth` and can be reloaded without retraining.

```python
torch.save(model.state_dict(), "mnist_model.pth")
```
## How to Run
```
pip install -r requirements.txt
jupyter notebook mnist_classifier.ipynb
```
## Dataset

The MNIST dataset is loaded using `touchvision.datasets.MNIST`, with automatic downloading if not found locally.

---
