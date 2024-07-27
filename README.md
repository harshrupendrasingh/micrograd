# micrograd
This Jupyter Notebook implements a basic neural network from scratch in Python. It covers neurons, layers, MLPs, forward/backward propagation, and visualization using Graphviz. Includes comparison with PyTorch.
# Micrograd

This notebook implements a simple automatic gradient calculation engine, inspired by Andrej Karpathy's micrograd library.

## Overview

The core component is the `Value` class, which represents a single scalar value and stores its gradient. Operations on `Value` objects automatically track dependencies and compute gradients using backpropagation.

The notebook demonstrates:

- Basic operations like addition, multiplication, power, tanh, and exp.
- Building a neural network with neurons and layers.
- Training the network using gradient descent on a simple dataset.

## Visualization

The `draw_dot` function visualizes the computation graph using graphviz, showing the data and gradient for each value.

## PyTorch Comparison

The notebook also includes a comparison with PyTorch, showing how to achieve the same results using PyTorch's automatic differentiation capabilities.
