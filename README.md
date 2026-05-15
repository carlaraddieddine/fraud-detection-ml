# Fraud Detection Using Machine Learning

## Project Overview
This project focuses on detecting fraudulent financial transactions using machine learning. The dataset is highly imbalanced, with fraud cases representing a very small percentage of all transactions, so the project uses evaluation metrics that are more suitable than accuracy alone.

## Objective
The goal of this project is to classify each transaction as either:
- Non-fraudulent
- Fraudulent

The project also compares models from both a technical performance perspective and a business cost perspective.

## Dataset
The dataset was obtained from Kaggle and contains credit card transaction records.

Dataset link: https://www.kaggle.com/datasets/kartik2112/fraud-detection

## Tools and Libraries
- Python
- pandas
- NumPy
- scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Models Implemented
- Logistic Regression
- Random Forest
- XGBoost
- Isolation Forest
- One-Class SVM

## Methodology
- Data preprocessing and missing value handling
- Feature engineering including transaction hour, day, weekday, and customer age
- Encoding categorical variables
- Scaling numerical features
- Model training and evaluation
- Cross-validation
- PCA comparison
- Feature importance analysis
- Business cost-based evaluation

## Evaluation Metrics
The models were evaluated using:
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

## Key Results
- XGBoost achieved the best overall machine learning performance.
- Random Forest achieved the lowest estimated business cost.
- PCA did not improve model performance.
- Transaction category and transaction time were among the most important fraud indicators.

## Files
- `Fraud_Detection.ipynb`: Main notebook implementation
- `Fraud Detection Report.pdf`: Full project report
- `Fraud Detection Presentation.pdf`: Project presentation

## Conclusion
This project shows that supervised machine learning models, especially XGBoost and Random Forest, can be effective for fraud detection when combined with proper preprocessing, suitable metrics for imbalanced data, and business-oriented evaluation.
