# Heart Disease Classification

## Overview

This GitHub repository contains code for a Heart Disease Classification project that utilizes machine learning techniques, including Logistic Regression, Random Forest, and Support Vector Machine (SVM), to predict heart disease based on medical data and risk factors. The project focuses on improving accuracy through feature engineering and ensemble modeling.

## Code

# Introduction
Heart disease is a significant health concern, and early detection is crucial for effective intervention. This project addresses this challenge by providing a machine learning solution for heart disease classification. It includes the following key components:

## Data Preprocessing: 
The dataset, containing various medical attributes and risk factors, is carefully processed. Missing values are handled, and the dataset is split into features (X) and the target variable (y).

## Exploratory Data Analysis (EDA): 
The project begins with EDA to gain insights into the data. Visualizations and summary statistics are used to understand the dataset's characteristics and relationships between features.

## Logistic Regression Model: 
An initial Logistic Regression model is built and evaluated for accuracy. Hyperparameter tuning is performed to find the best parameters for the Logistic Regression model, improving accuracy.

## Feature Engineering: 
Feature engineering techniques, such as squaring and calculating feature means, are applied to enhance the model's predictive power. A new Logistic Regression model is trained with these engineered features.

## Ensemble Modeling: 
An ensemble model is created by combining predictions from Random Forest, Logistic Regression, and SVM models. The ensemble uses soft voting based on class probabilities to provide accurate predictions.

## Running the Code
You can access the Jupyter Notebook containing the code in this repository.

## Results
Initial Logistic Regression Accuracy: 79.92%
Logistic Regression Accuracy After Hyperparameter Tuning: 87.88%
Logistic Regression Accuracy with Feature Engineering: 82.20%
Ensemble Model (Random Forest, Logistic Regression, SVM) Accuracy: 94.32%
The ensemble model demonstrates significant accuracy improvements, making it a valuable tool for early heart disease detection.

## Results

| Model                                  | Accuracy      |
| -------------------------------------- | ------------- |
| Initial Logistic Regression            | 79.92%        |
| Logistic Regression After Tuning       | 87.88%        |
| Logistic Regression with Engineering   | 82.20%        |
| Ensemble Model (Random Forest, Logistic Regression, SVM) | 94.32%        |

The ensemble model demonstrates significant accuracy improvements, making it a valuable tool for early heart disease detection.

## Conclusion
This Heart Disease Classification project showcases the power of machine learning in healthcare. By leveraging various modeling techniques and feature engineering, accurate predictions can be made, potentially saving lives through early detection of heart disease. This repository serves as a valuable resource for healthcare professionals and data scientists interested in predictive healthcare applications.

Feel free to explore the code, run the notebook, and adapt the techniques to your specific healthcare or classification projects.


