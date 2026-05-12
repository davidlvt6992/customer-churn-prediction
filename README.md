# Customer Churn Prediction

## Project Goal

The goal of this project is to build a machine learning model that predicts whether a customer is likely to churn.

This project is also a training project for practicing the full machine learning workflow, including:

- problem framing
- exploratory data analysis
- data cleaning and preprocessing
- baseline modeling
- model evaluation
- reproducibility
- documentation

## Problem Framing

This is a supervised binary classification problem.

Each row in the dataset represents one customer.

The target variable is `Churn`, which indicates whether a customer left the company.

The input features may include customer demographics, account information, subscribed services, contract type, payment method, tenure, and charges.

The model should predict the probability that a customer will churn.

## Why This Problem Matters

Customer churn prediction can help a business identify customers who are at risk of leaving.

A business could use this prediction to prioritize retention actions, such as customer support, discounts, or contract changes.

In this project, the focus is not only on model performance. The focus is also on building a valid, reproducible, and understandable machine learning workflow.

## Dataset
Dataset description:
This project uses Telco Customer Churn from Kaggle.
The dataset contains customer-level information for a telecommunications company. Each row represents a customer, each column contains some customer's attribute. The target column is `Churn`.

the dataset includes features related to : 
- Demographic info (gender, age, partners, dependents)
- Customer account information (monthly charges, payment method, contract etc)
- Signed services (phone, internet , streaming etc)

Dataset details:
- Source: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- File name: `WA_Fn-UseC_-Telco-Customer-Churn`
- Number of rows: 7043
- Number of columns: 21
- Target column: `Churn`

## Initial Success Criteria

The first version of this project will be considered successful if it includes:

- a clean project repository structure
- a clear problem definition
- basic exploratory data analysis
- a valid train/validation/test split
- a simple baseline model
- appropriate classification metrics
- clear documentation of results and limitations

## Planned Workflow

1. Set up the project repository.
2. Download and inspect the dataset.
3. Create a data dictionary.
4. Perform exploratory data analysis.
5. Identify missing values, duplicates, class imbalance, and leakage risks.
6. Build a preprocessing pipeline.
7. Train a dummy baseline model.
8. Train a logistic regression baseline.
9. Evaluate models using classification metrics.
10. Improve the model carefully.
11. Save the final model.
12. Document results, limitations, and next steps.

## Repository Structure

```text
customer-churn-prediction/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── src/
│   └── churn/
│       └── __init__.py
│
├── models/
├── reports/
│   └── figures/
└── tests/
```

## Setup

Setup instructions will be added after the project environment is finalized.

## Current Status 
Current Milestone - project setup and problem framing. 

Completed: 
- Folder structure
- README.md file 
- Initial requirements.txt (empty) file

Next: 
- Fill .gitignore
- Fill requirements.txt 
- Push initial commit to GitHub
- Download and inspect data
