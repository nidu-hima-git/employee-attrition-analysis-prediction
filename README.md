# Employee Attrition Analysis and Prediction

## Project Overview

Employee attrition is a major challenge for organizations because high turnover increases recruitment costs, reduces productivity, and impacts organizational performance.

This project analyzes employee attrition patterns and predicts whether employees are likely to leave using Machine Learning classification models.

The project applies:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

The study also includes ROC-AUC evaluation and employee risk segmentation for HR decision support.

---

## Objectives

- Identify employee attrition patterns through exploratory analysis.
- Determine key predictors influencing employee turnover.
- Build machine learning classification models.
- Compare model performance using evaluation metrics.
- Perform employee risk segmentation.

---

## Dataset

Source: Kaggle Employee Attrition Dataset
Dataset Link: https://www.kaggle.com/datasets/personacarved/employee-attrition-dataset 

Dataset includes:

- Age
- Monthly Income
- Job Satisfaction
- Work Life Balance
- Overtime
- Department
- Years at Company
- Performance Rating
- Promotion History

---

## Methods Used

### Data Preprocessing

✔ Missing value checking  
✔ Duplicate checking  
✔ Label Encoding  
✔ Feature Scaling  
✔ Class imbalance handling (`class_weight='balanced'`)

### Machine Learning Models

1. Logistic Regression
2. Decision Tree
3. Random Forest

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- AUC-ROC
- Confusion Matrix

---

## Key Findings

- Overtime significantly increases attrition risk.
- Job Satisfaction and Work-Life Balance strongly influence employee retention.
- Logistic Regression achieved the highest ROC-AUC score.
- Random Forest achieved the highest overall accuracy.
- Risk segmentation successfully identified High-Risk employees.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

Machine Learning / HR Analytics Project
