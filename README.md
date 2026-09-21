# Flood Prediction using Support Vector Regression

A machine learning project that applies **Support Vector Regression (SVR)** to predict flood-related outcomes from historical data.

The project focuses on data preprocessing, feature scaling, hyperparameter tuning, and model evaluation using Python and Scikit-learn.

---

## Project Overview

Flood prediction is a regression problem where historical environmental and/or flood-related data can be used to estimate a continuous target variable.

In this project, an SVR-based regression pipeline was developed and evaluated using historical data. Different SVR configurations were explored through systematic hyperparameter tuning using `GridSearchCV`.

The notebook demonstrates the complete workflow from data preparation to model evaluation.

---

## Workflow

The project follows these main steps:

1. Load and inspect the dataset
2. Perform data preprocessing
3. Prepare features and target variables
4. Split the data into training and testing sets
5. Standardize the input features
6. Train a Support Vector Regression model
7. Perform hyperparameter tuning using Grid Search
8. Generate predictions on the test data
9. Evaluate model performance

---

## Model

### Support Vector Regression (SVR)

The primary model used in this project is **Support Vector Regression**, implemented using Scikit-learn.

The model was explored with different:

- `C` values
- Kernel functions
- `gamma` values
- Polynomial degrees
- `epsilon` values

The hyperparameters were evaluated using `GridSearchCV` to identify a suitable configuration.

---

## Hyperparameter Tuning

The project uses `GridSearchCV` for systematic hyperparameter search.

The search space includes:

```python
C
kernel
gamma
degree
epsilon
