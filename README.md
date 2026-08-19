# Classical vs Deep Vision

This project compares a classical computer vision pipeline based on HOG features and an SVM classifier with a convolutional neural network implemented in PyTorch.

The models are evaluated on CIFAR-10 under both clean and degraded image conditions, including noise, blur, rotation, and occlusion.

## Project Goals

- Understand fundamental image representations
- Explore handcrafted HOG features
- Train a classical SVM classifier
- Build a CNN using PyTorch
- Evaluate model robustness under image degradation
- Compare classical and deep visual representations

## Dataset

CIFAR-10

## Methods

### Classical Vision
Image → Grayscale → HOG → SVM → Prediction

### Deep Vision
Image → CNN → Learned Features → Prediction

## Robustness Tests

- Gaussian noise
- Gaussian blur
- Rotation
- Occlusion

## Status

Project implementation and experiments are currently in progress.