Handwritten Digit Recognition using Neural Network

This project demonstrates a neural network model for recognizing handwritten digits using the MNIST dataset. The MNIST dataset consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9).

Project Overview

The goal of this project is to build and train a neural network to accurately classify handwritten digits. The model is implemented using TensorFlow and Keras, two powerful libraries for building and training machine learning models.

Dataset

The MNIST dataset is a benchmark dataset in the field of machine learning, particularly in the area of image recognition. It contains grayscale images of handwritten digits, each of size 28x28 pixels.

Model Architecture

The neural network model is built using the Sequential API from Keras. The architecture consists of the following layers:
Flatten Layer: Flattens the 28x28 input images into a 784-dimensional vector.

Dense Layer 1: Fully connected layer with 128 neurons and ReLU activation function.
Dense Layer 2: Fully connected layer with 64 neurons and ReLU activation function.
Output Layer: Fully connected layer with 10 neurons (one for each digit) and softmax activation function
