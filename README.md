# Credit Risk Model

## Overview

This repository contains a credit risk model built using Python and various data science libraries. The model aims to predict credit default risk based on several features such as credit utilization, age, past due history, debt ratio, monthly income, number of open credit lines, and number of dependents.

## Dataset

The dataset used for training and testing the model consists of two CSV files:
- `cs-training.csv`: Training data with features and labels.
- `cs-test.csv`: Test data with features but no labels.

The columns in the dataset include:
- `SeriousDlqin2yrs`: Binary label indicating whether the individual experienced financial distress in the past 2 years.
- `RevolvingUtilizationOfUnsecuredLines`: Ratio of total credit card balances to credit limits.
- `age`: Age of the individual.
- `NumberOfTime30-59DaysPastDueNotWorse`: Number of times the individual was 30-59 days past due on any credit account.
- `DebtRatio`: Ratio of monthly debt payments to monthly income.
- `MonthlyIncome`: Monthly income of the individual.
- `NumberOfOpenCreditLinesAndLoans`: Number of open credit lines and loans.
- `NumberOfTimes90DaysLate`: Number of times the individual was 90 days or more past due.
- `NumberRealEstateLoansOrLines`: Number of real estate loans or lines of credit.
- `NumberOfTime60-89DaysPastDueNotWorse`: Number of times the individual was 60-89 days past due but not worse in the last 2 years.
- `NumberOfDependents`: Number of dependents in the individual's family.

## Data Preprocessing

The data preprocessing steps included:
- Handling missing values in the `MonthlyIncome` and `NumberOfDependents` columns.
- Removing duplicate records from the dataset.
- Imputing missing values using appropriate strategies (e.g., median imputation).
- Filtering out extreme values and outliers.

## Model Building

The model building process involved:
- Exploratory data analysis (EDA) to understand the distribution and relationships among features.
- Feature engineering to create new features or transform existing ones.
- Training various machine learning algorithms such as logistic regression, random forest, or gradient boosting.
- Evaluating model performance using appropriate metrics such as accuracy, precision, recall, and ROC-AUC.
