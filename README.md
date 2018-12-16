# Basic Neural Network

## Objective

In this notebook I will create a Neural network on the Digits dataset, with a hidden layer using a sigmoid activation function and the last layer being a logistic regression layer.

I finally explore the impact of using not normalized data, different learning rates, different size of hidden layer and different epochs.

## Steps:

- Load the digits dataset
- Define the functions one_hot encoder, negative loglikelihood, softmax.
- Preprocess data using train test split, scaling and using the one hot encoding function.
- Define activation functions: Implement the ‘sigmoid’ and its element-wise derivative ‘dsigmoid’ functions
- Define the functions for the neural network: Implemented ‘forward’ and ‘forward_keep_activations’ functions (model with a hidden layer); ‘loss’, ‘predict’ and ‘accuracy’ functions are those for the Logistic Regression; the ‘grad_loss’ function computes the gradient of sample x with respect to the two W and bs; ‘train’ function similar to logistic regression but with W_h, b_h, W_o and b_h.
- Build and evaluate untrained model. We test the ‘loss’ and ‘train’ functions before training and plot predicted and true probabilities.
- Train for 35 epochs. Create loop to train for 35 epochs showing change in train loss, train acc and test acc. Plot graphs for probabilities, training loss and training accuracy.
- Repeat the exercise by exploring the impact of not normalized data, different learning rates, size of hidden layer and using different epochs.


## Requirements

Python 3 and the following modules: sklearn, numpy, matplotlib 



