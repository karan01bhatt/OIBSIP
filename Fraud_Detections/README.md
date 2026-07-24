# Credit Card Fraud Detection

## Overview
This project builds a machine learning pipeline to detect fraudulent credit card transactions using an imbalanced dataset. It addresses the class imbalance problem using SMOTE and compares multiple classification models.

## Objective
- Detect fraudulent transactions.
- Handle class imbalance using SMOTE.
- Compare Logistic Regression and Random Forest models.
- Evaluate using Precision, Recall, F1-Score and ROC-AUC.

## Dataset
Credit Card Fraud Detection Dataset (Kaggle)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

## Project Workflow
1. Load dataset
2. Data cleaning
3. Class imbalance analysis
4. Exploratory Data Analysis
5. Apply SMOTE
6. Train-Test Split
7. Logistic Regression
8. Random Forest
9. Model Evaluation
10. ROC Curve
11. Feature Importance
12. Fraud Detection Insights

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Results
Random Forest achieved better fraud detection performance compared to Logistic Regression, especially in identifying fraudulent transactions while maintaining high ROC-AUC.

## Project Structure

```
Fraud_Detection/
│
├── Dataset/
│   └── creditcard.csv
│
├── Images/
│
├── Fraud_Detection.ipynb
├── README.md
└── requirements.txt
```

## Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- Real-time fraud detection
- Model deployment using Flask/FastAPI