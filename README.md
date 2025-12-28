# Optimizing Classification Models Using Hyperparameter Tuning

## Overview
This project builds and optimizes tree-based classification models to predict whether an individual earns more than 50,000 USD per year using census demographic and employment-related features. It demonstrates an end-to-end machine learning workflow with a focus on performance and interpretability.

## Dataset
- Census income dataset  
- Target variable: Income (`<=50K`, `>50K`)
- Missing values represented using `'?'` and handled during preprocessing

## Workflow
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Model training and evaluation
- Hyperparameter tuning using RandomizedSearchCV
- Model comparison and interpretation

## Models Used
- Decision Tree Classifier (baseline)
- Random Forest Classifier
- Tuned Random Forest using RandomizedSearchCV

## Evaluation
- Accuracy, precision, recall, F1-score
- Confusion matrix visualizations
- Feature importance analysis

## Key Outcome
Hyperparameter tuning improved model performance, with the tuned Random Forest achieving the best generalization and accuracy.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
