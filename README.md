# credit-risk-classification

# Credit Risk Classification

## Overview
This repository contains a machine learning model for credit risk classification, developed as part of a financial analysis project. The model aims to predict the creditworthiness of borrowers based on historical lending data from a peer-to-peer lending services company. By accurately classifying loans as either "healthy" (low-risk) or "high-risk," the model can assist the company in making more informed lending decisions and mitigating potential financial losses.

## Data
The dataset used for this analysis is `lending_data.csv`, which contains historical lending data from the peer-to-peer lending services company. The dataset includes various features such as loan size, interest rate, borrower income, debt-to-income ratio, and more.

## Analysis

### Overview
The purpose of this analysis is to build a machine learning model that can predict the creditworthiness of borrowers based on the provided historical lending data. The goal is to create a model that can accurately classify loans as either "healthy" (low-risk) or "high-risk," which can help the company make more informed lending decisions and mitigate potential financial losses.

### Results
Using a logistic regression model, the following performance metrics were obtained:

- **Accuracy Score:** 0.99
- **Precision Score (Healthy Loans):** 1.00
- **Recall Score (Healthy Loans):** 0.99
- **Precision Score (High-Risk Loans):** 0.85
- **Recall Score (High-Risk Loans):** 0.91

### Summary
The logistic regression model demonstrated excellent performance in predicting both healthy and high-risk loans. For the healthy loan class, the model achieved near-perfect precision and recall scores, indicating that it can accurately identify low-risk loans with minimal false positives or false negatives.

For the high-risk loan class, the model exhibited good precision and recall scores, although slightly lower than the healthy loan class. This means that the model can effectively identify most high-risk loans while minimizing the number of false positives (healthy loans classified as high-risk).

The overall accuracy score of 0.99 further reinforces the model's strong predictive capabilities, correctly classifying 99% of the loan instances in the testing data.

Based on these results, I would recommend the company to implement this logistic regression model for their credit risk assessment process. The model's high accuracy and reliable performance in identifying both low-risk and high-risk loans can provide valuable insights and support informed lending decisions.

However, it's important to note that the model's performance may vary depending on the specific characteristics of the data and the evolving lending landscape. Continuous monitoring and periodic retraining of the model with new data may be necessary to maintain its predictive accuracy over time.

Additionally, the company should consider incorporating other relevant factors, such as economic conditions, industry trends, and regulatory changes, into their overall risk assessment strategy to ensure a comprehensive and up-to-date approach to credit risk management.

## Installation
To run this project locally, you'll need to have Python and the required libraries installed. You can install the necessary libraries by running the following command:

```bash
pip install -r requirements.txt
