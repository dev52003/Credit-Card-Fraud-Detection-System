# Credit Card Fraud Detection System

## Overview

This project focuses on detecting credit card fraud using various machine learning models. The objective is to identify fraudulent transactions from legitimate ones with high accuracy. Several models were compared to determine the most effective classifier for this task.

## Dataset

- **Source:** [Credit Card Fraud Detection Dataset 2023](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023) from Kaggle.
- **Description:** This dataset contains credit card transactions labeled as fraudulent or legitimate, providing a basis for training and evaluating the machine learning models.

## Models Compared

- **Logistic Regression:** `LogisticRegression()`
- **Decision Tree Classifier:** `DecisionTreeClassifier()`
- **Random Forest Classifier:** `RandomForestClassifier()`
- **Support Vector Classifier:** `SVC()`
- **K-Nearest Neighbors Classifier:** `KNeighborsClassifier()`
- **Gaussian Naive Bayes:** `GaussianNB()`
- **AdaBoost Classifier:** `AdaBoostClassifier()`
- **Gradient Boosting Classifier:** `GradientBoostingClassifier()`

## Results

After evaluating the models, the **Random Forest Classifier** achieved the highest accuracy of **99.98%**, making it the most effective model for this dataset.

## Methodology

1. **Data Preprocessing:** Cleaned and prepared the dataset for modeling, handling missing values, and balancing the classes.
2. **Model Training:** Trained each model using the preprocessed data.
3. **Evaluation:** Compared the models based on accuracy, precision, recall, and F1-score.
4. **Final Model:** Selected the Random Forest model due to its superior performance.
