# Credit Risk Classification
![pexels-ivan-samkov-7621136](https://github.com/SakinaJaffri/Credit-Risk-Classification/assets/146900226/5a686cb2-0495-4d43-904e-030900cd1160)

## Overview

This analysis focuses on training and evaluating a model for credit risk classification using historical lending data from a peer-to-peer lending company. The goal is to build a model that can accurately identify the creditworthiness of borrowers based on financial information.

## Methodology

- **Data Preparation**: Features such as loan size, interest rate, borrower income, etc., were identified and separated for predicting loan status.
- **Model Training**: A Logistic Regression model was trained using the identified features and loan status target variable.
- **Model Evaluation**: The model's performance was evaluated using accuracy score, confusion matrix, and classification report.

## Results

### Model 1: Logistic Regression with Original Data

- Achieved an accuracy score of 99% for both healthy and high-risk loans.
- Precision score: 100% for healthy loans and 85% for high-risk loans.
- Recall score: 99% for healthy loans and 91% for high-risk loans.

### Model 2: Logistic Regression with Resampled Data

- Achieved an accuracy score of 99% for both healthy and high-risk loans.
- Precision score: 100% for healthy loans and 84% for high-risk loans.
- Recall score: 99% for both healthy and high-risk loans.

## Summary

Both models demonstrate high accuracy, but Model 2 shows slightly lower precision compared to Model 1. However, Model 2 performs better in predicting high-risk loans, minimizing false positives. Therefore, it's recommended for its improved recall score in identifying high-risk loans, which is crucial for risk management.
