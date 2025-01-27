
# Cervical Cancer Risk Factors Analysis

## Overview
This repository provides a comprehensive analysis of cervical cancer risk factors using a variety of machine learning techniques. The project leverages clinical and demographic data to assess the correlation and importance of various features in predicting biopsy results and other diagnostic outcomes.

---

## Features
- **Exploratory Data Analysis (EDA)**:
  - Feature correlation and significance testing.
  - Box plots for demographic and clinical features.
- **Machine Learning Models**:
  - Logistic Regression
  - Random Forest Classifier
  - Decision Tree Classifier
  - Support Vector Classifier (SVC)
  - XGBoost Classifier
  - Multi-Layer Perceptron (MLP) Classifier
- **Performance Metrics**:
  - Accuracy, F1-score, Precision, Recall, Matthews Correlation Coefficient (MCC), Cohen's Kappa, Log Loss.
- **Feature Importance Visualization**:
  - Bar plots of feature importance scores for selected models.

---

## File Structure
- `cervical_cancer.py`: Main Python script containing data preprocessing, visualization, and machine learning pipelines.
- `data/`: Placeholder directory for input datasets (e.g., `Processed_risk_factors_cervical_cancer.csv`).
- `results/`: Contains generated plots, feature importance graphs, and model outputs.

---

## Requirements
The project uses the following Python packages:

| Package            | Version      |
|--------------------|--------------|
| `numpy`            | `1.21.6`     |
| `pandas`           | `1.3.5`      |
| `seaborn`          | `0.11.2`     |
| `matplotlib`       | `3.5.1`      |
| `scikit-learn`     | `1.0.2`      |
| `xgboost`          | `1.6.1`      |

You can install these dependencies via:
```bash
pip install -r requirements.txt
