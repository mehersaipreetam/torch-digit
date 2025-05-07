# torch-digit: Comparing Neural Networks in PyTorch

This repository demonstrates two approaches to building a simple neural network for digit classification on the MNIST dataset:

- **From Scratch** using only PyTorch tensors and autograd (`torch_digit.ipynb`)
- **Using PyTorch’s `nn.Module`** for a more concise and modular implementation (`torch_digit_nn.ipynb`)

## Features

- 3-layer feedforward neural network (2 hidden layers)
- Manual weight initialization and gradient descent in the custom version
- `nn.Module`-based implementation for comparison
- Cross-entropy loss for multi-class classification
- Trained and evaluated on the MNIST dataset
- Supporting code and design notes included to aid understanding

## Architectures

**Common Architecture (for both notebooks):**

- **Input Layer:** 784 units (flattened 28x28 image)
- **Hidden Layer 1:** 256 units, ReLU or Tanh activation
- **Hidden Layer 2:** 128 units, ReLU or Tanh activation
- **Output Layer:** 10 units (class scores for digits 0–9)

## Getting Started

### Prerequisites

- Python 3.7+
- PyTorch
- torchvision

Install dependencies:

```bash
pip install torch torchvision
```

Feel free to share any feedback or suggestions. I would be happy to add anything that helps improve clarity and understanding.