# credit-risk-classification
# Credit Risk Analysis

## Overview
The purpose of this analysis is to assess credit risk using a logistic regression model. The model predicts whether a loan is healthy or at high risk of default, based on customer financial attributes.

## Results
- **Accuracy Score**: 0.99
- **Precision Score**:
  - Healthy Loans (0): 1.00
  - High-Risk Loans (1): 0.85
- **Recall Score**:
  - Healthy Loans (0): 1.00
  - High-Risk Loans (1): 0.91

## Summary
The logistic regression model performs with very high accuracy in classifying healthy loans and shows good performance in identifying high-risk loans. With a precision of 85% and a recall of 91% for high-risk loans, the model is effective but may still occasionally miss or misclassify risky loans.

### Recommendation:
Given its high accuracy and solid precision-recall performance, this model is suitable for credit risk evaluation. However, for even more robust performance, especially for high-risk detection, exploring ensemble models such as Random Forest or Gradient Boosting is recommended.
