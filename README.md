# Mulilayer Perceptron 

## Introduction

The aim of this project was to implement MLP from scratch using Tensorflow (Subclassing API). 

** Subtasks**
1. Implementaion of model
2. Visualisation of cost function and accuracy plots, confusion matrix
3. Visualisation of misclassfied examples by class and exploration of probable soures of errors

** Model architecture  **
    - Fully connected layer 128 neurons and ReLU activation function
    - Fully connected layer with 10 neurons and the Softmax activation function
    
   ** Learning hyperparameters **
    - Batch size: 100
    - Optimizer: Adam
    - Learning factor: 0.001
    - Number of epochs: 10
    - Cost function: tf.keras.losses.SparseCategoricalCrossentropy


## Implementation

Neural network model was implemented using Tensorflow library  in Jupyter Notebook. The goal was to classify objects from CIFAR-10 dataset.  
