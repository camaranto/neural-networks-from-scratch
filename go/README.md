# Neural Networks from Scratch on GO
Based on the tutorial [Neural net with go](https://datadan.io/blog/neural-net-with-go)

This project provides a neural network built from scratch using the Go programming language. The network is designed for simple classification tasks and uses a single hidden layer architecture with a sigmoid activation function [1-3]. The primary goal is to showcase how to implement a neural network without relying on external machine learning libraries or CGO, emphasizing Go's native numerical capabilities.

The original project uses the classic Iris flower dataset, and was expanded to support more datasets.
You can learn the basics neural networks concept like:

- Backpropagation: The algorithm used to train the network by adjusting weights and biases based on errors.
- Feedforward: The process of passing input data through the network to generate predictions.
- Matrix operations: GoNum is used for matrix manipulations, essential for neural network computations.
- Stochastic Gradient Descent (SGD): The optimization technique employed to update network parameters during training.

The provided code includes functions for data loading, network initialization, training, prediction, and accuracy calculation.
