Fashion MNIST Classification with PyTorch
This notebook demonstrates a simple image classification task using the Fashion MNIST dataset and a basic neural network implemented with PyTorch.

Project Description
The goal of this project is to build and train a neural network to classify images of clothing items from the Fashion MNIST dataset. The dataset consists of 60,000 training images and 10,000 test images, each being a 28x28 grayscale image, associated with a label from 10 classes (e.g., T-shirt/top, trousers, pullover, dress, coat, sandal, shirt, sneaker, bag, ankle boot).

The notebook covers the following steps:

Data Loading and Exploration: Loading the Fashion MNIST dataset from a CSV file and visualizing some sample images.
Data Preprocessing: Splitting the data into training and testing sets and normalizing the pixel values.
Custom Dataset and DataLoader: Creating a custom PyTorch Dataset and DataLoader for efficient data handling during training.
Model Definition: Defining a simple feedforward neural network using PyTorch's nn.Module.
Training: Training the neural network using stochastic gradient descent and Cross-Entropy Loss.
Evaluation: Evaluating the trained model's accuracy on the test set.
Setup and Requirements
To run this notebook, you will need to have the following libraries installed:

pandas
numpy
scikit-learn
torch
matplotlib
