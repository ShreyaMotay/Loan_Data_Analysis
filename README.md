# Loan Data Analysis Project

## Overview
This project focuses on analyzing loan data to predict loan approval status using machine learning models. The dataset includes various features such as age, income, employment experience, loan amount, credit score, and more. The goal is to build predictive models to determine whether a loan application will be approved or not.

## Features
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling features.
- **Exploratory Data Analysis (EDA)**: Visualizing data distributions, correlations, and feature importance.
- **Model Training**: Implementing machine learning models including Gaussian Naive Bayes, Random Forest, and Logistic Regression.
- **Evaluation**: Assessing model performance using accuracy, confusion matrices, and classification reports.
- **Prediction**: Predicting loan approval status for new customer data.

## Dataset
The dataset (`Loan_Data.csv`) contains the following columns:
- **Features**: `age`, `gender`, `education`, `income`, `employment_experience`, `home_ownership`, `loan amount`, `loan_intent`, `loan_int_rate`, `loan_percent_income`, `credit_history_length`, `credit_score`, `loan_default_history`.
- **Target Variable**: `loan_status` (approved or not approved).

## Results
- **Gaussian Naive Bayes Accuracy**: 81.84%.
- **Dicision Tree**: 91.20%.
- **Random Forest Accuracy**: 87%.
- **Key Features**: Income, credit score, and loan amount were among the most important features for predicting loan approval.

## Usage
1. **Requirements**:
   - Python 3.x
   - Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.

2. **Steps**:
   - Clone the repository:
     ```bash
     git clone https://github.com/ShreyaMotay/Loan-Data-Analysis.git
     ```
   - Install dependencies:
     ```bash
     pip install pandas numpy scikit-learn matplotlib seaborn
     ```
   - Run the Jupyter notebook:
     ```bash
     jupyter notebook Loan_data_analysis.ipynb
     ```
