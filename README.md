# Regression and Classification with Python

This repository contains a Jupyter notebook that demonstrates the core ideas behind supervised machine learning, with a focus on regression and classification techniques.

The notebook walks through:

- Linear regression with synthetic data
- Matrix-based closed-form solutions
- Gradient descent, stochastic gradient descent, and mini-batch training
- Polynomial regression and model flexibility
- Regularization with Ridge, Lasso, and Elastic Net
- Logistic regression for binary classification
- Classification using the Iris dataset

## Notebook

- `regression_and_classification.ipynb`

## Overview

The project explores how machine learning models learn from data and how different techniques affect prediction accuracy, bias-variance tradeoff, and generalization.

It starts with a simple linear relationship and then expands into more advanced methods such as polynomial features and regularization. The final section applies logistic regression to classify Iris flowers by petal width and visualizes the probability curve and decision boundary.

## Topics Covered

### Linear Regression
- Synthetic data generation
- Least squares with the normal equation
- Comparison of closed-form and scikit-learn solutions

### Optimization
- Gradient descent
- Stochastic gradient descent (SGD)
- Mini-batch training

### Polynomial Regression
- Modeling nonlinear relationships using higher-degree features
- Observing underfitting and overfitting behavior
- Learning curves and model complexity

### Regularization
- Ridge regression (`L2`)
- Lasso regression (`L1`)
- Elastic Net (combined `L1` + `L2`)

### Logistic Regression
- Sigmoid function
- Binary classification
- Probability prediction and decision boundary
- Iris dataset example

## Requirements

Make sure you have Python installed, then install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

## How to Run

1. Open the notebook in Jupyter or VS Code.
2. Run the cells in order.
3. Explore the visualizations and model outputs.

Example:

```bash
jupyter notebook regression_and_classification.ipynb
```

## Project Structure

```text
.
├── regression_and_classification.ipynb
├── README.md
```

## Learning Goals

By the end of this notebook, you should understand:

- how linear regression works mathematically
- how optimization algorithms train models
- why polynomial features can improve nonlinear fitting
- how regularization prevents overfitting
- how logistic regression predicts class probabilities

## Notes

This notebook is intended for educational and learning purposes. It is a practical walkthrough of common machine learning concepts using Python and scikit-learn.

## License

This project is provided for educational use. Add your preferred license if you plan to publish it publicly on GitHub.
