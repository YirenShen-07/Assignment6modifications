# Assignment6modifications
# German Credit Risk Analysis

## Overview
This project analyzes the German Credit Risk dataset using various machine learning interpretability techniques. The goal is to understand how different features influence credit risk predictions using a Logistic Regression model.

## Dataset
The German Credit Risk dataset contains 1000 credit applications with the following features:

### Numerical Features:
- **Age**: The age of the credit applicant
- **Credit amount**: The amount of credit requested
- **Duration**: The duration of the credit in months
- **Job**: The employment category of the applicant

### Categorical Features:
- **Sex**: The applicant's gender (male/female)
- **Housing**: Type of housing (own/rent/free)
- **Saving accounts**: Status of saving accounts (little/moderate/quite rich/rich/unknown)
- **Checking account**: Status of checking accounts (little/moderate/rich/unknown)
- **Purpose**: Purpose of the credit (car/furniture/radio/TV/education/business/etc.)

### Target Variable:
- **Risk**: Credit risk classification (good/bad)

## Methods
The analysis includes:
- **Correlation Analysis of numeric features**: Identifies relationships among numerical features and potential multicollinearity.
- **Partial Dependence Plots (PDP)**: Provides global feature influence, showing how average predictions change with different feature values.
- **Individual Conditional Expectation (ICE) plots**: Offers individualized explanations of feature effects, revealing heterogeneous responses across samples.
- **Accumulated Local Effects (ALE) plots**: Provides a more accurate depiction of local and non-linear feature effects, particularly when features are correlated.
- **Feature Importance Analysis using permutation importance**: Ranks features based on their contribution to model predictions.
