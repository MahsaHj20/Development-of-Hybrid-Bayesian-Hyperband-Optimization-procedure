
 **********************************************************************************
 Readme File for Development of Hybrid Bayesian-Hyperband Optimization procedure  
 **********************************************************************************
## Requirements
- Python 3.x
- numpy
- pandas
- scikit-learn

## Installation
You can install the required packages using pip:


## Description
 This script loads a sample regression dataset, splits it into training and testing sets,
 defines a search space for hyperparameters, and performs hyperparameter optimization using Hybrid Bayesian-Hyperband algorithm.
 It then trains an AdaBoost regressor with the best hyperparameters and makes predictions on a test dataset.

## Dataset
The script loads a sample dataset from a CSV file named "Train" which is a training dataset. You can replace it with your own dataset by modifying the file path in the script.

## Hyperparameters
- n_estimators: Number of estimators in the ensemble (10 to 500).
- learning_rate: Learning rate of the boosting algorithm (0.01 to 1.0).
- loss: Loss function to be optimized ('linear', 'square', 'exponential').
- estimator: Base estimator for the ensemble ('DecisionTreeRegressor', 'RandomForestRegressor', 'SVR').

## Results
The script prints the best hyperparameters found during optimization and the final predictions made by the trained model on the Test dataset.

