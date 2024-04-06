# Credit Card Fraud Detection

## Overview

This project focuses on building a machine learning model for credit card fraud detection. Credit card fraud is a significant concern for both credit card companies and cardholders. Detecting fraudulent transactions accurately is crucial to prevent financial losses. The dataset used contains transactions made by credit cards in September 2013 by European cardholders.

## Problem Statement

The objective of this project is to develop a classification model that can effectively identify fraudulent transactions. The dataset is highly imbalanced, with fraud cases accounting for a very small percentage of total transactions.

## Approach

### Data Preparation
- Read the dataset from a CSV file
- Perform exploratory data analysis (EDA) to understand the data
- Handle missing values and outliers
- Standardize the 'Amount' column using feature scaling
- Check for data imbalance and apply appropriate techniques (undersampling and oversampling in this case)

### Model Building
- Implement logistic regression, decision tree, and random forest classifiers
- Train the models using the balanced dataset
- Evaluate model performance using accuracy, precision, recall, F1-score, and ROC AUC metrics
- Select the best performing model for deployment

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Usage

To run the project, follow these steps:

1. Clone the repository.
2. Install dependencies listed in requirements.txt.
3. Execute the main script file.

## Results

The Random Forest model achieved the highest accuracy among the tested classifiers. Further hyperparameter tuning and model optimization can potentially improve the model's performance.

## Future Work

- Experiment with advanced feature engineering techniques
- Explore ensemble methods for model improvement
- Implement real-time fraud detection system
- Deploy the model in a production environment

## Contributors

- [Name - Rishabh Yadav]
- [GitHub Profile _ RishabhYadav626]
