# **Customer Churn Prediction**

## **Project Overview**
This project aims to predict customer churn for a telecommunications company. Churn prediction involves identifying customers who are likely to leave the service in the near future. By analyzing customer behavior and attributes, this project provides actionable insights to improve customer retention strategies.

## **Dataset**
- **Source:** IBM Telco Customer Churn Dataset.
- **Attributes:**
  - Includes demographic information (e.g., gender, senior citizen status), service details (e.g., internet service type), and billing information (e.g., monthly and total charges).
  - The target variable is `Churn`, indicating whether the customer left the service (Yes/No).
- **Characteristics:**
  - Data imbalance observed in the target variable, with a churn ratio of approximately 73:27.

## **Methodology**
1. **Data Preprocessing:**
   - Handled missing values in the `TotalCharges` column by removing rows with null values (less than 0.2% of the dataset).
   - Converted categorical variables into numerical format using encoding techniques.
   - Rescaled numerical features to standardize data for better model performance.

2. **Exploratory Data Analysis:**
   - Visualized key patterns and relationships between features and churn.
   - Compared distributions of key features (e.g., monthly charges, tenure) for churned and non-churned customers.

3. **Data Balancing:**
   - Addressed the data imbalance using SMOTE-ENN to generate a balanced dataset.

4. **Modeling:**
   - Built and evaluated multiple machine learning models, including:
     - Logistic Regression
     - Decision Tree Classifier
   - Evaluated models based on accuracy, precision, recall, and F1-score.

## **Results**
- Logistic Regression achieved [accuracy, precision, recall, F1-score] (add metrics from notebook).
- Decision Tree Classifier achieved [accuracy, precision, recall, F1-score] (add metrics from notebook).
- The use of SMOTE-ENN significantly improved model performance on imbalanced data.

## **Conclusion**
This project demonstrates the importance of data preprocessing and resampling techniques in churn prediction. Logistic Regression provided interpretable results, while the Decision Tree model captured complex patterns effectively. These models can help telecom companies proactively address customer churn and enhance customer satisfaction.
