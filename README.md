# Loan_Default_Detection
# Loan Default Detection

This project applies machine learning techniques to predict whether a loan will default, using customer and loan-related features. It aims to support financial institutions in assessing credit risk and making data-driven lending decisions.


## Overview

The goal of this project is to identify high-risk loans by building a classification model. We use a dataset containing demographic and financial information of loan applicants and train various models including Logistic Regression and Gradient Boosting.

## Dataset

The dataset includes features such as:

- Loan Amount
- Annual Income
- Employment Length
- Credit History Length
- Debt-to-Income Ratio
- Loan Purpose
- Delinquencies

The target variable is a binary indicator of whether the loan resulted in default.

## Features

Data preprocessing steps include:

- Handling missing values
- Encoding categorical variables
- Feature scaling
- Feature selection

## Modeling

We explore and evaluate multiple models:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Model performance is measured using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Results

XGBoost performed best in terms of F1-Score and ROC-AUC, with strong precision-recall tradeoffs, indicating suitability for imbalanced classification.
