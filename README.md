# Credit Risk Classification

![Credit Risk](https://github.com/SakinaJaffri/Credit-Risk-Classification/assets/146900226/5a686cb2-0495-4d43-904e-030900cd1160)

## Overview

This project focuses on building and evaluating a model to classify credit risk using historical lending data from a peer-to-peer lending company. The objective is to accurately determine the creditworthiness of borrowers based on financial data and loan history.

## Methodology

### Data Preparation
- Identified key features such as **loan size**, **interest rate**, **borrower income**, and other relevant factors to predict loan status.
- Split the data into features (X) and target variable (y) for training the model.

### Model Training
- Used **Logistic Regression** as the classification model to predict the likelihood of a loan being "healthy" or "high-risk."
- Trained two models:
  1. **Model 1**: Using original data.
  2. **Model 2**: Using resampled data to balance the classes.

### Model Evaluation
- Evaluated both models using:
  - **Accuracy Score**
  - **Confusion Matrix**
  - **Classification Report** (Precision, Recall, and F1-Score)

## Results

### Model 1: Logistic Regression with Original Data
- **Accuracy Score**: 99%
- **Precision**: 
  - Healthy Loans: 100%
  - High-Risk Loans: 85%
- **Recall**:
  - Healthy Loans: 99%
  - High-Risk Loans: 91%

### Model 2: Logistic Regression with Resampled Data
- **Accuracy Score**: 99%
- **Precision**:
  - Healthy Loans: 100%
  - High-Risk Loans: 84%
- **Recall**:
  - Healthy Loans: 99%
  - High-Risk Loans: 99%

## Summary

Both models demonstrate high accuracy. While **Model 1** has higher precision for high-risk loans, **Model 2** provides improved recall for high-risk loans, reducing false negatives. This makes Model 2 better suited for identifying high-risk loans, which is critical for effective risk management.

## Technologies Used
- **Python**
- **Pandas**
- **Logistic Regression**
- **Scikit-learn**

## How to Run
1. Clone the repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the Jupyter Notebook to train and evaluate the models.

## Contributors
- **Sakina Jaffri** - Project Developer
