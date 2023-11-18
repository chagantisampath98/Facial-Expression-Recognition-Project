# Facial Expression Recognition Project

## Overview

This project aims to develop a Convolutional Neural Network (CNN) for facial expression recognition using deep learning techniques. The model is designed to classify facial images into different emotion categories, providing a basis for understanding and interpreting human emotions from images.

## CNN Architecture

The CNN architecture is designed with the following key features:

- **Convolutional Layers:** Four convolutional layers with tanh activation functions and 3x3 kernel size for feature extraction.
- **Pooling Layers:** Max-pooling layers with a 2x2 pool size for down-sampling.
- **Dropout Layers:** Applied after each pooling layer to prevent overfitting.
- **Fully Connected Layers:** Two fully connected layers with 128 and 512 neurons, respectively, using tanh activation.
- **Output Layer:** Output layer with softmax activation for emotion classification.

## Training

The model is trained for 15 epochs using the training dataset, and its performance is evaluated on the validation dataset. The training progress, including loss and accuracy, is visualized using the livelossplot library.

## Hyperparameters

The model hyperparameters are optimized using the hyperopt library, resulting in the selection of tanh activation, Adam optimizer, 128 dense layers, and a 3x3 kernel size.

Feel free to explore the project! If you have any questions or suggestions, please open an issue or reach out to the project maintainers.

