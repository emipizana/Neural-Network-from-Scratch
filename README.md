# Neural Network from Scratch

This project implements a neural network for handwritten digit recognition (MNIST dataset) using two approaches:
1. Building a neural network from scratch using only NumPy and pandas
2. Creating an equivalent model using Keras for comparison

## Project Overview

The main goal is to understand the fundamentals of neural networks by implementing one without high-level libraries, then comparing it with a Keras implementation to validate the approach and highlight the advantages of deep learning frameworks.

## Implementation Details

### Neural Network from Scratch
- **Architecture**: 784 (input) → 20 (hidden) → 10 (output) neurons
- **Activation Functions**: ReLU for hidden layer, Softmax for output layer
- **Loss Function**: Categorical Cross-Entropy
- **Training Algorithm**: Gradient Descent
- **Key Components Implemented**:
  - Forward propagation
  - Backpropagation
  - Weight initialization
  - Gradient descent optimization

### Keras Implementation
- Implements an equivalent model architecture using Keras
- Uses the same activation functions and layer sizes
- Compares performance with the from-scratch implementation

## Results

- **From-Scratch Model**:
  - Training accuracy: ~91.5%
  - Test accuracy: ~91.3%
- **Keras Model**:
  - Training accuracy: ~99.2%
  - Test accuracy: ~97.9%

The higher accuracy of the Keras model demonstrates the advantages of using established frameworks with optimized implementations.

## Key Features

- Visualization of training accuracy over time
- Visualization of sample predictions
- Analysis of incorrectly classified digits
- Comparison between custom and framework implementations

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- TensorFlow/Keras

## Usage

1. Clone the repository
2. Run the Jupyter notebook to see the step-by-step implementation and results

## Learning Outcomes

This project provides hands-on experience with:
- The mathematical foundations of neural networks
- Backpropagation algorithm implementation
- Weight update strategies
- Matrix operations for neural network computations
- The advantages of deep learning frameworks

## Acknowledgements

Based on the approach outlined in "Neural Network from scratch in Python" by O. Aflak (2018).
