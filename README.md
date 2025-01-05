# Loan Approval Prediction

This project leverages machine learning techniques to predict loan approval status based on applicants' financial and demographic attributes. It applies various classification algorithms and preprocessing techniques to optimize prediction accuracy.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Overview](#dataset-overview)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
4. [Models Used](#models-used)
5. [Results](#results)
6. [Conclusion](#conclusion)
7. [Future Work](#future-work)
8. [References](#references)

## Introduction
The aim is to create a system that predicts loan approval using a data-driven approach. The project addresses challenges such as data dimensionality and imbalance by utilizing techniques like PCA, outlier removal, and ensemble learning.

## Dataset Overview
- **Features**: Includes CIBIL score, income, employment status, loan term, loan amount, and asset value.
- **Target Variable**: Loan status (approved/rejected).
- **Source**: Historical loan applications.
- **Size**: 100,514 records with 19 features.
- **Issues Addressed**:
  - Missing values
  - Imbalanced target variable

## Exploratory Data Analysis
- Visualized distributions for categorical and numerical variables.
- Examined correlations to select key predictors.
- Removed low-frequency categories to streamline analysis.

## Models Used
1. **Logistic Regression**
2. **Support Vector Machine (SVM)**
3. **Naive Bayes**
4. **Ensemble Model (Maximum Voting)**

Each model was trained and evaluated on a preprocessed dataset, and performance was assessed using metrics like accuracy, precision, recall, and F1-score.

## Results
The ensemble model outperformed individual models:
- **Accuracy**: 85.68%
- **Precision**: 86.83%
- **Recall**: 85.68%
- **F1-Score**: 83.40%

## Conclusion
The ensemble model was the most reliable for predicting loan approval, demonstrating the benefits of combining diverse models.

## Future Work
- Experiment with hyperparameter tuning.
- Explore additional ensemble methods like bagging and boosting.
- Integrate external financial data to improve model robustness.

## References
1. [Scikit-learn Documentation](https://scikit-learn.org/)
2. [Seaborn Documentation](https://seaborn.pydata.org/)
3. "The Elements of Statistical Learning" by Hastie, Tibshirani, and Friedman.
