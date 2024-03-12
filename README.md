# Diabetes Prediction Model

This repository contains a Python script for predicting diabetes based on various health metrics. The script uses the Pima Indians Diabetes Database to train and test different models, including K-Nearest Neighbors, Naive Bayes, and Logistic Regression, for predicting diabetes diagnoses.

## Dataset

The dataset includes the following features:
- Number of pregnancies
- Glucose concentration
- Blood pressure 
- Skin
- Insulin level
- Body mass index (BMI)
- Diabetes inheritance
- Age

The target variable is a binary classification indicating the presence(1) or absence(0) of diabetes.

## Dependencies

- Python
- Numpy
- Pandas
- Scikit-learn

Ensure you have the above dependencies installed before running the script.

## Usage

1. Clone this repository to your local machine.
2. Place the `diabetes.csv` dataset in the same directory as the script.
3. Run the script using Python

   
## Features

- Data preprocessing, including handling missing values and normalization.
- Splitting the dataset into training and testing sets.
- Training K-Nearest Neighbors, Naive Bayes, and Logistic Regression models on the training set.
- Evaluating model performance with metrics like accuracy, mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE).


