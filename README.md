# Fraud Detection – Exploratory Machine Learning Project

## Project Overview
This project explores a fraud detection problem using classical machine learning models.
The goal is not to build a production-ready system, but to deeply understand how different
classification models behave in the context of an imbalanced dataset.

All analysis, reasoning, and results are fully documented inside the Jupyter Notebook.

## Problem Statement
Fraud detection is a binary classification problem where the positive class (fraud)
is rare. This makes model evaluation non-trivial, as high accuracy can be misleading.
The project focuses on understanding trade-offs between recall, precision, and F1-score.

## Dataset
- Tabular dataset with numerical features
- Strong class imbalance
- Target variable indicates fraudulent vs non-fraudulent transactions

## Approach
The project follows a notebook-driven, exploratory workflow:
1. Data exploration and understanding
2. Data preprocessing (scaling, encoding where necessary)
3. Model training using multiple classification algorithms
4. Evaluation using appropriate metrics for imbalanced data
5. Model comparison and interpretation

## Models Used
- Logistic Regression (baseline, interpretability)
- Random Forest Classifier (ensemble learning)
- CatBoost Classifier (gradient boosting with strong generalization)
- LightGBM Classifier (efficient gradient boosting)

The purpose of using multiple models is to understand their behavior and limitations,
not to optimize for maximum performance.

## Evaluation Metrics
Given the imbalance of the dataset, evaluation focuses on:
- Precision
- Recall
- F1-score
- Confusion Matrix

Accuracy is reported but not used as the primary decision metric.

## Key Learnings
- Why accuracy is unreliable for fraud detection
- How different models react to class imbalance
- Trade-offs between interpretability and performance
- Importance of metric selection based on business context

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Cost-sensitive learning
- Advanced ensemble methods (e.g., gradient boosting)
- Feature engineering informed by domain knowledge

## How to Run
1. Clone the repository
2. Install dependencies
3. Open the notebook and run cells sequentially
