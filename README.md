# phase_3_project


# Diabetes Classification Project

## Project Overview

This project focuses on building a predictive model to help healthcare providers identify high-risk patients for diabetes. The goal is to enable timely interventions and better resource allocation. We use various machine learning models and techniques to analyze and predict diabetes risk based on patient data.

## Table of Contents

- [Data Description](#data-description)
- [Data Preparation](#data-preparation)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Recommendation](#conclusion)

- ## Data Description

The dataset used for this project is `diabetes.csv`, which contains patient data including features like BMI, age, and glucose levels. The target variable is whether a patient has diabetes.

## Data Preparation

1. **Handling Missing Data:** Missing values were addressed through imputation or removal, depending on the extent of missingness.
2. **Feature Engineering:** Features were scaled and transformed as needed. Polynomial features were generated to capture non-linear relationships.
3. **Train-Test Split:** The data was split into training and testing sets to evaluate model performance on unseen data.
4. **Scaling:** Features were scaled to ensure compatibility with distance-based models.

## Modeling

The project explores several classification models:

1. **Logistic Regression:** A baseline model to establish initial performance metrics.
2. **Decision Tree:** Analyzing nonparametric modeling to handle complex feature interactions.
3. **Random Forest:** An ensemble method to improve prediction accuracy and handle overfitting.

Each model was tuned using hyperparameter optimization techniques.

## Evaluation

Model performance was evaluated using the following metrics:

- **Accuracy:** Overall correctness of the model's predictions.
- **ROC-AUC:** Ability to distinguish between classes.
- **Precision and Recall:** Performance metrics, especially important in the context of class imbalance.

## Results

- **Logistic Regression:** Achieved an accuracy of 0.74 and ROC-AUC of 0.80.
- **Decision Tree:** Showed improved interpretability but was prone to overfitting.
- **Random Forest:** Delivered the best performance with an accuracy of 0.76 and ROC-AUC of 0.80.


##Recommendation


- **Random Forest is the best model overall because it balances precision, recall, and accuracy effectively while also having a high ROC-AUC score. It should provide the best trade-off between correctly identifying high-risk patients and minimizing false positives, making it the most suitable choice for your classification problem.



- **Focus on Middle-Aged Adults: Healthcare interventions might be particularly beneficial for individuals in their late 20s to mid-40s, as these age groups have higher numbers of diabetes cases.

- **Targeted Interventions: Healthcare providers should consider closely monitoring and offering lifestyle interventions to individuals with BMI over 25, particularly as they approach BMI levels where higher diabetes rates are observed (e.g., above BMI 27).


