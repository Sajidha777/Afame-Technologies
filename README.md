# Customer Churn Prediction Project

## Project Overview
This project aims to predict customer churn for a U.S. bank dataset. Churn prediction is crucial for businesses as it helps in identifying customers who are likely to leave and so implement retention strategies. Using historical customer data, we can analyse to gain insights, and develop machine learning models to predict churn.

## Dataset
The dataset consists of historical data from a U.S. bank's customers. It includes various features such as customer demographics and other information which will help predict whether a particular customer will leave the bank or not.

## Notebooks

### 1. Analysis.ipynb
- Data exploration and visualization
- Analysis to gain insights into the dataset

### 2. preprocessing-and-model.ipynb
- Data preprocessing steps such as encoding categorical variables, scaling numerical features, and balancing the dataset
- Model building and evaluation using various algorithms
- Hyperparameter tuning and model comparison

## Models
The models evaluated in this project are:
- *Logistic Regression*
- *Random Forest*
- *Gradient Boosting*
- *Support Vector Machine (SVM)*

## Results
The performance of the models was evaluated using metrics such as accuracy, precision, recall, F1 score, and ROC AUC. The models were compared based on the evaluation.
Depending on the business objectives, different thresholds can be chosen for the trained models, leading to various precision-recall trade-offs. As the threshold increases, the precision improves but the recall decreases, highlighting the trade-off between capturing more actual churners and minimizing false positives.

