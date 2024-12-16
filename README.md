# Customer Segmentation and Churn Prediction

This repository contains two key projects that are part of a larger customer segmentation initiative. These projects focus on clustering customers based on purchasing behaviors and predicting customer churn using machine learning techniques. Together, they contribute to building a comprehensive understanding of customer behavior and improving retention strategies.

## Table of Contents

- [Overview](#overview)
- [Projects](#projects)
  - [RFM Cluster Analysis](#rfm-cluster-analysis)
  - [Churn Prediction Model](#churn-prediction-model)
- [Usage](#usage)

## Overview

The projects in this repository aim to segment customers and predict churn to enable targeted marketing and retention strategies. The key objectives include:
1. Understanding customer behavior through Recency, Frequency, and Monetary (RFM) analysis.
2. Building a robust model to predict customer churn and inform intervention efforts.

## Projects

### RFM Cluster Analysis

This project involves segmenting customers based on RFM (Recency, Frequency, and Monetary) analysis to identify behavioral clusters. Key steps include:

1. **Data Import and Exploration**  
   Data is prepared and explored for meaningful patterns.

2. **Cluster Analysis**  
   K-means clustering is used to group customers into distinct segments based on their RFM scores.

3. **Insights and Recommendations**  
   Clusters are analyzed to provide actionable insights for marketing strategies.

### Churn Prediction Model

#### Overview

The churn prediction model is developed using a dataset containing customer behavior data, including account activity, transaction history, and demographic information. The primary objective is to predict the target variable FLAG, which indicates whether a customer has churned.

#### Key Features:
- Data preprocessing and feature engineering
- Handling class imbalance through resampling techniques
- Model selection (Random Forest, Decision Tree, etc.)
- Performance evaluation using accuracy, precision, recall, and F1-score

#### Data

The dataset includes various columns such as:
- **Demographic data:** Age, gender, customer sector, and industry
- **Account information:** Active accounts, transaction counts, turnover data
- **Behavioral data:** Mobile payments, ATM and POS transactions
  more were dropped on importation
#### Modeling Approach

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

## Usage

1. Navigate to the respective project directories:
- RFM_cluster_analysis.ipynb: Contains the analysis and clustering steps.
- Churn_Prediction_Model_v2.ipynb: Details the churn prediction pipeline.
