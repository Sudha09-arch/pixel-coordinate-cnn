# Pixel Coordinate Prediction using CNN

## Overview
This project trains a Convolutional Neural Network (CNN) to predict the
(x, y) coordinates of a single bright pixel in a 50×50 grayscale image.

## Dataset
- Synthetic dataset generated programmatically
- Each image contains exactly one bright pixel
- Target output is the normalized pixel coordinate

## Model
- Two convolution layers with ReLU and MaxPooling
- Fully connected regression output layer
- Loss Function: Mean Squared Error (MSE)
- Optimizer: Adam

## Results
- Model successfully predicts pixel coordinates
- Achieved pixel error distance < 1 pixel
- Demonstrates effective spatial learning

## Installation
