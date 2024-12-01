
# Linear Regression - Hands-On Assignment

### Overview
In this assignment, we implement Linear Regression to predict the progression of diabetes in patients using two approaches:
1. **Using Scikit-learn's linear regression model.**
2. **Custom implementation using gradient descent.**

---

## Dataset
- **Source**: [Diabetes Dataset](https://www4.stat.ncsu.edu/~boos/var.select/diabetes.html).
- **Description**:
  - Contains data from **442 diabetes patients**.
  - **10 Features**: Age, Sex, Body Mass Index, Average Blood Pressure, and six blood serum measurements.
  - **Target**: Quantitative measure of disease progression after one year.
- **Structure**:
  - `diabetes.data`: Features matrix (442x10).
  - `diabetes.target`: Targets vector.

---

## Task 1: Linear Regression with Scikit-learn
Using Scikit-learn's `LinearRegression` class to train and test the model.


## Task 2: Custom Linear Regression Implementation (Gradient Descent)
### Steps
1. Initialize weights (`W`) and bias (`b`).
2. Use the gradient descent algorithm to minimize the cost function (Mean Squared Error - MSE).
3. Update parameters iteratively to achieve convergence.

## Sanity Check
- **Compare Results**: Validate custom implementation by comparing the MSE and coefficients with Scikit-learn's results.
- **Threshold**: Acceptable difference of ±1% between the two implementations.

---

## Notes
- Ensure the learning rate and number of epochs are tuned to achieve convergence.
- The custom implementation should be tested thoroughly to match Scikit-learn's results.

