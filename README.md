# Housing Prices Prediction

## Overview
I  developed this project to predict housing prices using linear regression. The workflow includes preprocessing the dataset, implementing different tricks (Simple Trick, Absolute Trick, Square Trick), and applying linear regression both from scratch and using built-in functions.

## Data Preprocessing
Before implementing regression models, I cleaned and preprocessed the dataset appropriately. The preprocessing steps include:

1. **Handling Missing Values**.
2. **Feature Scaling**.
3. **Encoding Categorical Variables**.

## Tricks for Optimization
### Simple Trick
- Uses the mean of target values to minimize the mean squared error.

### Absolute Trick
- Utilizes the median of target values to minimize the mean absolute error.

### Square Trick
- Minimizes the sum of squared differences between predicted and actual values.

## Linear Regression Implementation
### From Scratch
I implemented linear regression using the following steps:
1. Compute the cost function (Mean Squared Error).
2. Compute gradients and update weights using Gradient Descent.
3. Train the model iteratively until convergence.

### Using Built-in Functions
comparing my implementation with `sklearn.linear_model.LinearRegression`, which simplifies the process by automatically optimizing parameters.
