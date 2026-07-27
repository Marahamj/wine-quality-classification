# wine-quality-classification


# Wine Quality Classification using SVM and XGBoost

## Overview

This project focuses on binary classification of wine quality using Machine Learning techniques. The Red Wine and White Wine Quality datasets were combined, preprocessed, and used to compare the performance of Support Vector Machines (Hard Margin & Soft Margin) with the XGBoost classifier.

---

## Dataset

- Wine Quality (Red)
- Wine Quality (White)

The datasets include physicochemical properties such as:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

The target variable was converted into binary classification:

- **1** → Good Wine (Quality ≥ 6)
- **0** → Poor Wine (Quality < 6)

---

## Project Workflow

- Load and merge datasets
- Data preprocessing
- Feature engineering
- Binary target creation
- Feature scaling using StandardScaler
- Train/Test split
- Hard Margin SVM
- Soft Margin SVM
- XGBoost Classifier
- Performance evaluation
- ROC Curve comparison

---

## Technologies

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Machine Learning Techniques

- Data Preprocessing
- Feature Scaling
- Binary Classification
- Hard Margin Support Vector Machine
- Soft Margin Support Vector Machine
- Gradient Boosting (XGBoost)

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve
- ROC-AUC Score
- Classification Report

---

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Feature Scaling
- Machine Learning Model Development
- Binary Classification
- Model Comparison
- Performance Evaluation
- Data Visualization

---

## Results

Model comparison showed that:

| Model | Accuracy | ROC-AUC |
|--------|---------:|---------:|
| Hard Margin SVM | ~73.6% | ~0.79 |
| Soft Margin SVM | ~73.6% | ~0.79 |
| XGBoost | **~76.3%** | **~0.82** |


---

## Author

Marah A Qandeel
