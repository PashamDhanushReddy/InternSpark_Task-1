# Machine Learning Classification Project Report

## Executive Summary
This project focuses on building a supervised machine learning classification model to predict whether a breast tumor is malignant or benign based on the Breast Cancer Wisconsin dataset. We evaluated two models: Logistic Regression and Random Forest Classifier. 

The Logistic Regression model outperformed the Random Forest model across all key metrics on this dataset, achieving an accuracy of 98.25%.

## Methodology

### 1. Dataset
- **Source**: `scikit-learn` built-in Breast Cancer Wisconsin dataset.
- **Task**: Binary classification (Malignant vs. Benign).

### 2. Preprocessing
- **Train/Test Split**: 80% training data, 20% testing data (stratified split to maintain class proportions).
- **Scaling**: Applied `StandardScaler` to normalize features (crucial for Logistic Regression convergence and performance).

### 3. Models Compared
1. **Logistic Regression**: A linear model effective for binary classification.
2. **Random Forest Classifier**: An ensemble learning method using multiple decision trees.

## Evaluation Results

Models were evaluated on the 20% test set.

| Metric | Logistic Regression | Random Forest |
|--------|---------------------|---------------|
| **Accuracy** | 98.25% | 95.61% |
| **Precision** | 98.61% | 95.89% |
| **Recall** | 98.61% | 97.22% |
| **F1 Score** | 98.61% | 96.55% |
| **ROC-AUC** | 99.54% | 99.37% |

## Conclusion
The **Logistic Regression** model provides the best predictive performance for this specific dataset. The `StandardScaler` preprocessing step significantly benefited its performance, leading it to outscore the Random Forest model in accuracy, precision, recall, and ROC-AUC. 

All code, data pipelines, and visualizations (ROC curve and Confusion Matrices) are available in the accompanying Jupyter Notebook (`breast_cancer_classification.ipynb`).
