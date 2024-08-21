# Logistic Regression on Diabetes Dataset with MinMaxScaler

This project demonstrates the use of logistic regression to predict the likelihood of diabetes in patients based on various health indicators. The dataset is preprocessed using MinMaxScaler to ensure that all features contribute equally to the model's predictions.

## Overview

- **Objective**: To develop a predictive model that identifies whether a patient has diabetes based on their medical data.
- **Dataset**: `diabetes.csv`, containing information such as glucose levels, BMI, insulin levels, and age.
- **Preprocessing**: Applied MinMaxScaler to normalize the feature values between 0 and 1, improving the efficiency of the logistic regression model.
- **Modeling**: Utilized Logistic Regression for binary classification into diabetic and non-diabetic categories.

## Project Structure

- **Python Script**: The main code file includes:
  - Data loading and exploration
  - Feature scaling using MinMaxScaler
  - Model training and prediction
  - Performance evaluation through accuracy, confusion matrix, and classification report
- **Dataset**: The dataset used is included as `diabetes.csv`.

## Results

- The model's accuracy and other metrics are printed at the end of the script, giving you insights into its performance.
