# Optimization Algorithms Implementation in Python

This project explores first and second-order optimization techniques for training a linear regression model. I implemented three algorithms: Adam, Gradient Descent with Momentum (GDM), and BFGS. The project investigates the performance differences between these optimizers on two datasets:

- `Dummy Marketing and Sales Data`
- `Car Purchasing Model`

### The code is implemented as a Python class with the following functionalities:

- Vectorized implementation: Efficiently handles calculations using vector operations.
- Optimizer selection: Selects the desired optimizer (Adam, GDM, or BFGS) through an instance variable.
- Batch, mini-batch, and stochastic support: Adapts to different training approaches.
- Performance tracking: Records cost function values and model parameter values for each iteration.

### The project analyzes and compares the results:

- Learning curves: Plots cost function vs. iterations to visualize optimization progress.
- Parameter influence: Plots cost function vs. each model parameter to understand their impact.
- Hyperparameter tuning: Runs various scenarios with different batch sizes and hyperparameter combinations.
- BFGS comparison: Compares the performance of L-BFGS (second-order method) to first-order optimizers.

### Skills:

- Implement first and second-order optimization algorithms.
- Train linear regression models using various optimizers.
- Analyze learning curves and parameter influence.
- Compare and interpret results from different optimization techniques.

