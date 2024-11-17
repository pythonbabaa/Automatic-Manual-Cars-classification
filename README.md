# Car Gear Prediction using Machine Learning

This project involves analyzing car dataset features to predict the gear type (manual or automatic) using various machine learning classification models. It includes preprocessing, exploratory data analysis, model training, evaluation, and visualization.

## Table of Contents
1. [Features](#features)
2. [Requirements](#requirements)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Evaluation](#model-evaluation)
5. [Usage Instructions](#usage-instructions)
6. [Visualizations](#visualizations)

---

## Features
- **Data Cleaning**: Handles missing values, duplicates, and irrelevant columns.
- **Feature Scaling**: Normalizes data for efficient model training.
- **Model Training**: Implements Logistic Regression, Decision Trees, Random Forest, SVM, K-Nearest Neighbors, and Naive Bayes classifiers.
- **Evaluation**: Calculates accuracy, confusion matrix, and ROC-AUC for model comparison.
- **Visualization**: Plots decision trees, confusion matrices, and ROC curves.

---

## Requirements
Install the following Python libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels dtreeviz
for fpr, tpr, model, auc_score in zip(fpr_list, tpr_list, model_list, auc_list):
    plt.plot(fpr, tpr, label=f"{model} (AUC={auc_score:.3f})")
plt.xlabel("False Positive Rate")
plt.ylabel("True Positive Rate")
plt.legend(loc="lower right")
plt.title("ROC Curve")
plt.show()

---

Save this content as `README.md` in your project directory. Let me know if you'd like further assistance!
