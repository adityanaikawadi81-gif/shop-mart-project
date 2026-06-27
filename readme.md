## Project Overview

This project predicts whether an online visitor will complete a purchase based on their browsing behavior on an e-commerce website.

The project was developed as part of a Machine Learning assignment using the **ShopSmart Online Shoppers Purchasing Intention Dataset**. A Decision Tree Classifier is built after performing data preprocessing, exploratory data analysis (EDA), feature engineering, and hyperparameter tuning with pruning techniques.

Since the dataset is imbalanced, the model is evaluated primarily using the **F1-Score** instead of Accuracy.

## Problem Statement

An e-commerce company wants to identify visitors who are most likely to purchase products.

By analyzing customer browsing sessions such as:

- Number of pages visited
- Time spent on pages
- Bounce Rate
- Exit Rate
- Traffic Source
- Visitor Type
- Weekend Visit
- Month

the model predicts whether a customer will generate revenue (Purchase = Yes/No).

---

##  Dataset

Dataset: Online Shoppers Purchasing Intention Dataset

Target Variable:

```
Revenue
```

- TRUE → Customer made a purchase
- FALSE → Customer did not purchase

Dataset contains both

- Numerical Features
- Categorical Features

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

```
Data Collection
       │
       ▼
Data Preprocessing
       │
       ▼
Exploratory Data Analysis
       │
       ▼
Feature Encoding
       │
       ▼
Train-Test Split
       │
       ▼
Decision Tree Classifier
       │
       ▼
Tree Pruning
       │
       ▼
Model Evaluation
```

---

## Data Preprocessing

The following preprocessing steps were performed:

- Missing value checking
- Duplicate value removal
- Label Encoding
- One-Hot Encoding (if required)
- Feature Transformation
- Handling categorical variables
- Train-Test Split

---

## Machine Learning Model

Model Used:

- Decision Tree Classifier

## 📏 Evaluation Metrics

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

Since the dataset is imbalanced, **F1 Score** is considered the most important evaluation metric.

---

