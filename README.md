# Breast Cancer Classification using PCA and Logistic Regression

This repository contains a Python notebook demonstrating breast cancer classification using Principal Component Analysis (PCA) for dimensionality reduction and Logistic Regression for prediction.

## Overview

The notebook performs the following steps:

1. **Data Loading and Preparation:** Loads the breast cancer dataset from scikit-learn, converts it to a Pandas DataFrame, and standardizes the features using `StandardScaler`.

2. **Principal Component Analysis (PCA):** Applies PCA to reduce the dimensionality of the data. A scree plot is generated to visualize the cumulative explained variance, helping to determine the optimal number of principal components.  The data is then reduced to 2 principal components.  A scatterplot of the PCA results visualizes the separation of the two classes in the reduced feature space.

3. **Logistic Regression Modeling:** Trains a Logistic Regression model on the data reduced by PCA.  The model is trained and evaluated on a training and test set.

4. **Model Evaluation:** Evaluates the model's performance using accuracy, classification report, and a confusion matrix.  The model is shown to have high accuracy and precision on the test set.

## Dependencies

- `scikit-learn`
- `pandas`
- `matplotlib`
- `seaborn`

## Usage
Install the required dependencies:
    
