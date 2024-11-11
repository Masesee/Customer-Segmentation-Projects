# Churn Prediction Model

This project focuses on building a churn prediction model to predict customer churn in a given dataset. The goal is to predict whether a customer will churn (leave the service) based on various features, using machine learning techniques.

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Modeling Approach](#modeling-approach)
- [Evaluation](#evaluation)
- [Usage](#usage)

## Overview

The churn prediction model is developed using a dataset containing customer behavior data, including account activity, transaction history, and demographic information. The primary objective is to predict the target variable `FLAG`, which indicates whether a customer has churned.

### Key Features:
- Data preprocessing and feature engineering
- Handling class imbalance through resampling techniques
- Model selection (Random Forest, Decision Tree, etc.)
- Performance evaluation using accuracy, precision, recall, and F1-score

## Data

The dataset includes various columns such as:
- **Demographic data:** Age, gender, customer sector, and industry
- **Account information:** Active accounts, transaction counts, turnover data
- **Behavioral data:** Mobile payments, ATM and POS transactions
  more were dropped on importation
## Modeling Approach

1. **Preprocessing:**
   - Data cleaning (missing values, data type handling)
   - Feature scaling and encoding
   - Addressing class imbalance using techniques like SMOTE

2. **Modeling:**
   - A Random Forest Classifier is used to build the churn prediction model.
   - Hyperparameter tuning is performed to optimize model performance.

3. **Evaluation:**
   - Model performance is assessed using classification metrics: accuracy, precision, recall, and F1-score.
   - A confusion matrix provides insight into the model's ability to predict both churned and non-churned customers.

