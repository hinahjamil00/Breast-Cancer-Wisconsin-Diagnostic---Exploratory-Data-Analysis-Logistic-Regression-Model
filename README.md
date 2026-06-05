# Breast Cancer Wisconsin (Diagnostic) - ML Analysis

## Overview
This project performs Exploratory Data Analysis (EDA), Feature Engineering, and Machine Learning modeling on the Breast Cancer Wisconsin (Diagnostic) dataset to classify tumors as Benign or Malignant.

## Objective
To build a predictive classification model using medical diagnostic features and evaluate its performance using statistical and machine learning techniques.

## Dataset
- 569 samples
- 30 numerical features extracted from cell nuclei images
- Target: Diagnosis (M = Malignant, B = Benign)
- No missing values after cleaning

## Workflow
- Data Cleaning (removed unnecessary columns)
- Exploratory Data Analysis (distributions, correlations, outliers)
- Feature Engineering (interaction & ratio features)
- Train-Test Split (stratified sampling)
- Feature Scaling (Standardization)
- Cross Validation (5-fold)
- Model Training (Logistic Regression)
- Model Evaluation (Accuracy, Precision, Recall, F1-score, ROC-AUC)

## Key Insights
- Strong correlation among radius, perimeter, and area features
- Malignant tumors show higher values in size-related attributes
- Dataset is moderately imbalanced but manageable with stratification

## Model Performance
- Logistic Regression used as baseline classifier
- High accuracy and stable cross-validation scores
- Good class separation observed in PCA visualization

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Conclusion
The study demonstrates that properly scaled features and basic feature engineering significantly improve classification performance for breast cancer diagnosis.
