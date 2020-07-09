# Charity Data

This module includes a Python Notebook defining, fitting, and saving a neural network model to predict the success of Alphabet Soup's ventures.

The model I saved as "trained_model.h5" uses 33 input columns, into a dense hidden layer of 10 ReLU nodes, into a dense hidden layer of 6 ReLU nodes, into a single sigmoid output layer.

The model went through 100 epochs of fitting.

The model performance was ok, with an accuracy of 72.5%. This is below the desired threshold of 75%, but close. I attempted fitting models with more nodes, different activation functions, and different optimizer algorithms, but found "trained_model.h5" to be a simple, but still well-performing model once fitted.

I think this problem may benefit from a more complex model than, for example, a SVN or logistic regression. However, a random forest model could make for another interesting way to account for nonlinearities in the classification problem.
