# Employee Churn Prediction Using MachineLearning

## Overview

This project predicts employee attrition using machine learning techniques. It utilizes various classifiers such as Logistic Regression, Decision Tree, Random Forest, and XGBoost to predict whether an employee is likely to leave the organization based on features such as satisfaction level, last evaluation, number of projects, average monthly hours, time spent in the company, work accidents, promotions in the last 5 years, department, and salary.

The workflow involves data preprocessing steps including handling duplicate values, scaling numerical features, and encoding categorical features using techniques like One-Hot Encoding and Ordinal Encoding. The dataset is then split into training and testing sets for model training and evaluation.

## Key Features

- Data preprocessing using pandas and scikit-learn
- Implementation of various machine learning algorithms including Logistic Regression, Decision Tree, Random Forest, and XGBoost
- Model evaluation using accuracy, precision, and recall scores
- Using Column Transformer and Pipeline to automate the whole process
