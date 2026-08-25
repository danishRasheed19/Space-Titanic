# Spaceship Titanic Prediction

Machine learning project for the [Kaggle Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic) competition.

## Overview

The goal is to predict whether passengers were **Transported** to another dimension based on passenger information and spending data.

## Approach

- Exploratory Data Analysis
- Feature engineering
- Missing value imputation
- Categorical encoding
- Feature scaling
- 5-fold Stratified Cross-Validation
- Baseline comparison of multiple classification models
- Hyperparameter tuning using GridSearchCV
- Soft Voting ensemble

## Models

- Gaussian Naive Bayes
- Logistic Regression
- K-Nearest Neighbors
- SVC
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- Voting Classifier

## Results

The best individual tuned model was **Gradient Boosting**, achieving an accuracy of approximately **80.38%** on the test data.

| Model | Accuracy |
|---|---:|
| XGBoost | 80.20% |
| Gradient Boosting | **80.38%** |
| Random Forest | 79.21% |
| Logistic Regression | 79.38% |
| Soft Voting Classifier | 80.31% |


## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
