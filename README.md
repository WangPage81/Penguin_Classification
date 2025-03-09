# Penguin Classification Using Neural Network

This repository contains a neural network model built using PyTorch to classify penguins into three species: **Adelie**, **Chinstrap**, and **Gentoo**. The model uses features such as bill length, bill depth, flipper length, and body mass to predict the species of penguins.

## Overview

The model is trained using the **Palmer Penguins dataset**. It uses a fully connected neural network (FCNN) with one hidden layer. The network architecture is designed to predict one of the three penguin species based on the following input features:

- Bill Length (mm)
- Bill Depth (mm)
- Flipper Length (mm)
- Body Mass (g)

The output is the predicted class of the penguin (i.e., its species).

### Model Architecture

- **Input Layer**: 4 input features (bill length, bill depth, flipper length, body mass).
- **Hidden Layer**: 10 neurons with ReLU activation.
- **Output Layer**: 3 neurons with a softmax activation function for multi-class classification.

### Libraries Used
- PyTorch
- NumPy
- Matplotlib
- Pandas

# Script
 /model/penguin_classifier.py 

# data
/data/penguins.csv

# Model 
/architecture and training script/penguin_classifier.pt 
