# Linear-Regression-from-Scratch

## Overview
This project demonstrates three approaches to Linear Regression:

* Linear Regression from Scratch using Gradient Descent.
* Scikit-learn's LinearRegression (Closed-form solution).
* Scikit-learn's SGDRegressor (Stochastic Gradient Descent).
* The project showcases the implementation of these techniques on a dataset, highlights how to optimize model parameters, and compares their results.

## Methods
1. Linear Regression from Scratch with Gradient Descent
We implement a linear regression model using gradient descent to iteratively optimize the weights (w) and bias (b), minimizing the cost function. This method is helpful to understand the mathematics behind model training.

Steps:
Initialization: Randomly initialize w and b.
Cost Function: Calculate the mean squared error between predictions and actual values.
Gradient Descent: Update w and b iteratively using the gradient of the cost function until convergence or until the maximum number of iterations is reached.

2. Scikit-learn's LinearRegression (Closed-Form)
This method solves the normal equation to compute the optimal weights and bias directly. It is computationally efficient for small datasets, as it requires no iterations.

3. Scikit-learn's SGDRegressor
This method uses stochastic gradient descent to find the best-fitting line. It updates the weights and bias iteratively, making it scalable to large datasets.
