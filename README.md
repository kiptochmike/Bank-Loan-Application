# Loan Approval Prediction Model

## Overview

This project aims to build and evaluate a machine learning model to automate the loan approval process for a bank, thereby reducing manual processing costs and improving decision accuracy. 

## Dataset

The dataset consists of various features related to loan applications, including both numerical and categorical data. The target variable indicates whether a loan was approved (AR) or not approved (No AR).

## Models Used

1. **Logistic Regression**
2. **Decision Tree**
3. **Random Forest**
4. **Support Vector Machine (SVM)**
5. **XGBoost**

## Feature Engineering

- Encoded categorical variables.
- Scaled numerical features.

## Model Evaluation

Evaluated models using:
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve

## Threshold Optimization

- Determined the optimal threshold to minimize the total cost.
- Calculated costs for false positives (FP) and false negatives (FN).
- Selected a threshold of 0.59, resulting in the minimum cost.

## Results

- **Optimal Threshold**: 0.59
- **Total Cost with Model**: 17,448 EUR
- **Manual Processing Cost**: 17,613 EUR
- **Cost Savings**: 165 EUR

## Visualizations

- **Confusion Matrix**: Visual representation of the model's performance.
- **Feature Importance**: Top 5 most important features influencing the model.
- **Cost vs. Threshold Plot**: Shows the total cost for different thresholds.
- **Business Impact Bar Plot**: Comparison of total costs with and without the model.

## Implementation

To implement the model in live decisions:
1. Preprocess new loan application data similarly to training data.
2. Predict probabilities using the logistic regression model.
3. Apply the threshold of 0.59 to make the final decision.
4. Automate the decision-making process to reduce manual efforts and costs.

