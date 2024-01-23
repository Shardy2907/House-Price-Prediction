# XGBoost Regression Model for Boston House Pricing Prediction

## Overview

This repository contains the code and resources for building a prediction model using XGBoost regression combined with RandomizedSearchCV for hyperparameter tuning. The model is trained and evaluated on the Boston House Pricing dataset available on Kaggle.

## Dataset

The Boston House Pricing dataset is available on Kaggle: [Boston Housing Prices dataset](https://www.kaggle.com/vikrishnan/boston-house-prices)

- **Dataset Description:** The dataset includes various features related to housing in Boston and the target variable is the median value of owner-occupied homes in $1000s.
- **Dataset Structure:**
  - `housing.csv`: CSV file containing the measurements and corresponding labels.

## Model Training and Hyperparameter Tuning
The XGBoost regression model is fine-tuned using RandomizedSearchCV for hyperparameter optimization. The search space includes parameters such as learning rate, max depth, number of estimators, subsample, colsample_bytree, and gamma.

## Evaluation
The model's performance is evaluated using mean squared error on the test set. The evaluation results and best hyperparameters are printed in the notebook.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.
