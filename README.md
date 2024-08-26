# Customer Churn Prediction: EDA and Classifier Models

This repository contains a project focused on analyzing and predicting customer churn. Customer churn is a critical issue for businesses, and predicting which customers are likely to leave can help companies take proactive measures to retain them.

## Project Overview

The project consists of the following main steps:

1. **Exploratory Data Analysis (EDA):** Understanding the dataset, visualizing patterns, and identifying important features that contribute to customer churn.
2. **Modeling:** Training and evaluating various machine learning classifiers to predict customer churn based on historical data.
3. **Evaluation:** Comparing model performances using different metrics such as accuracy and precision, and selecting the best model.

## Dataset

The dataset used in this project is the **Telco Customer Churn** dataset from IBM. It contains information on 7,043 customers from a fictional telco company in California, including demographics, services used, and whether the customer churned. This data is used to predict customer churn based on various factors like customer satisfaction, contract type, and services.

You can find the dataset and additional details at the following link:

[IBM Telco Customer Churn Dataset](https://www.ibm.com/communities/analytics/watson-analytics-blog/guide-to-sample-datasets/#telco-customer-churn-dataset)

## Methodology

### Data Cleaning and Preprocessing:
- Handle missing data.
- Encode categorical variables.
- Scale numerical features if necessary.

### Exploratory Data Analysis:
- Generate summary statistics.
- Visualize data distributions and relationships between features.

### Model Training:
Multiple classifiers were trained, including:
- Logistic Regression
- Decision Trees
- Random Forest
- XGBoost
- Support Vector Classifier (SVC)

Models were evaluated using cross-validation and performance metrics.

### Model Evaluation:
Performance was assessed based on accuracy, precision, recall, and other relevant metrics. The best-performing model was selected for deployment.

## Results

The results of the models, including the confusion matrix, accuracy, precision, and other evaluation metrics, are discussed in the notebook. The top-performing model(s) are highlighted.

## Repository Contents
- **`eda-classifier-models-for-customer-churn.ipynb`:** Jupyter Notebook containing the full analysis, model training, and evaluation process.
- **`data/`:** Folder containing the dataset used for this project (if publicly available).
- **`README.md`:** This file providing an overview of the project.

## Conclusion

This project demonstrates the importance of EDA and the use of multiple machine learning classifiers to predict customer churn. The best model can be deployed to help businesses take proactive measures to reduce churn and retain their customers.

## Kaggle Notebook

You can find the detailed analysis and code on my Kaggle notebook: [Link to Kaggle Notebook]([your-kaggle-notebook-link](https://www.kaggle.com/code/adarshrajmaurya/eda-classifier-models-for-customer-churn))
