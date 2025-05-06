# Simple Neural Network from Scratch using PyTorch

This repository contains an educational implementation of a basic fully-connected neural network built from scratch using only PyTorch tensors and autograd — no `nn.Module` or `torch.optim` used.

## 🔧 Features

- 3-layer feedforward neural network (2 hidden layers)
- Manual weight initialization and gradient descent
- Custom forward and backward pass logic
- Cross-entropy loss for multi-class classification
- Trained on the MNIST dataset

## 🧠 Architecture

- **Input Layer:** 784 units (flattened 28x28 images)
- **Hidden Layer 1:** 256 units with ReLU activation
- **Hidden Layer 2:** 128 units with ReLU activation
- **Output Layer:** 10 units (class scores)

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- PyTorch
- torchvision

Install dependencies:

```bash
pip install torch torchvision
```