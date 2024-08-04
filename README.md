
## Startup profit predictor

## Overview
This project aims to predict the profit of startups based on various features such as R&D Spend, Administration, Marketing Spend, and the state of the startup. The model is built using multiple linear regression.


## Dataset
The dataset used is 50_Startups.csv, which includes:

✔ R&D Spend
✔ Administration
✔ Marketing Spend
✔ State (Categorical: California, Florida, New York)
✔ Profit


## Files
✔ 50_Startups.csv: Dataset file.
✔ startup_profit_predictor.py: Script to train and save the model.
✔ finalized_mult_linear_regression_model.sav: Saved model file.

## Dependencies
pandas
scikit-learn
pickle

## Code Explanation
The script performs the following steps:

Loads the dataset and preprocesses the categorical data.
Splits the data into training and testing sets.
Trains a multiple linear regression model.
Evaluates the model using R-squared score.
Saves the trained model using pickle.
Loads the saved model and makes predictions.
