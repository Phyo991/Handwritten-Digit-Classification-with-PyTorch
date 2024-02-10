# Handwritten Digit Classification with PyTorch

Welcome to my project on handwritten digit classification using PyTorch! based on a Coursera project from the computer vision course. This repository contains my implementation of a Softmax classifier designed to accurately recognize and classify digits from the iconic MNIST dataset. The goal of this project is to demonstrate the application of PyTorch in building a simple yet powerful neural network for image classification.

## Project Overview

The project follows a straightforward machine learning workflow, starting from data preparation to model training and evaluation. Here's what you can expect to find in this repository:

- Data preparation scripts for loading and transforming the MNIST dataset.
- A PyTorch implementation of a Softmax classifier.
- Training and evaluation scripts, including loss and accuracy monitoring.
- A detailed Jupyter notebook that walks through the entire process.
- Visualizations of model parameters and predictions to interpret the model's performance.

## Getting Started

### Prerequisites

Ensure you have the following installed to get started with the project:

- Python 3.8 or newer
- PyTorch 1.8 or newer
- torchvision
- matplotlib for plotting
- numpy for numerical computations


Running the Project
Clone this repository to your local machine.
Navigate to the project directory.
Open the Jupyter notebook Digit_Classification_with_Softmax.ipynb to see the walkthrough.
Run the cells in the notebook to train the model and see the results.
Model Architecture
The model is a simple neural network with one linear layer, followed by a Softmax function to classify the digits into one of ten categories (0 through 9). The choice of a Softmax classifier is due to its effectiveness in multiclass classification problems, especially when dealing with mutually exclusive classes.

Training and Results
The model is trained using the Stochastic Gradient Descent (SGD) optimizer with a Cross-Entropy loss function, which is suitable for classification tasks. The training process is detailed in the notebook, including how to set up the data loaders, define the model, and execute the training loop.

After training, the notebook guides you through analyzing the model's performance, including accuracy metrics and visualizations of the learned weights.

