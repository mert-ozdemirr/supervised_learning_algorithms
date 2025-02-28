# Supervised Learning Models: Logistic Regression, SVM, and Decision Tree

This project explores three supervised learning models (Logistic Regression, Support Vector Machines, and Decision Tree) applied to different datasets, focusing custom implementation for Logistic Regession and sklearn-based implementation for SVM and Decision Trees.

Key Components:
* Logistic Regression (from scratch) – Implemented without using external machine learning libraries like sklearn, showcasing its mathematical foundation and weight updates. Applied to the Portuguese Bank Marketing Dataset (numeric, random subsampled).
* Support Vector Machine (SVM) (using sklearn) – A margin-based classifier applied to the Portuguese Bank Marketing Dataset for binary classification.
* Decision Tree (using sklearn) – A tree-based model trained on the Weights & BMI Dataset (6-class classification problem) to explore interpretability and hierarchical decision-making.

This project provides a hands-on approach to understanding supervised classification techniques and comparing their effectiveness.

## Results: Model Performance Comparison
The table below compares the evaluation metrics for Logistic Regression (from scratch) and SVM (sklearn) on the Portuguese Bank Marketing Dataset (numeric, random subsampled):

## Results: Model Performance Comparison

The table below compares the evaluation metrics for **Logistic Regression (from scratch)** and **SVM (sklearn)** on the **Portuguese Bank Marketing Dataset (numeric, random subsampled)**:

| Metric    | Logistic Regression | SVM      |
|-----------|---------------------|----------|
| Accuracy  | 0.8124              | 0.8207   |
| Precision | 0.7932              | 0.8099   |
| Recall    | 0.8436              | 0.8207   |
| F1-Score  | 0.8176              | 0.8153   |



## Results: Decision Tree Confusion Matrix and Classification Report

![image](https://github.com/user-attachments/assets/e265a111-2abd-42ef-8791-3129d2e0809c)

Classification Report:
              precision    recall  f1-score   support

           1       0.52      0.63      0.57       119
           2       0.80      0.83      0.82       112
           3       0.74      0.79      0.76       112
           4       0.82      0.75      0.78       106
           5       0.76      0.69      0.72       106
           6       0.80      0.68      0.74       117

    accuracy                           0.73       672
   macro avg       0.74      0.73      0.73       672
weighted avg       0.74      0.73      0.73       672

## Results: Decision Tree Visualization

![image](https://github.com/user-attachments/assets/84dcbd5d-acc7-4c92-bad1-472a2c76ca1c)

