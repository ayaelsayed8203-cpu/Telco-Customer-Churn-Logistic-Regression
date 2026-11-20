# Telco-Customer-Churn-Logistic-Regression

## Project Overview

This project demonstrates the complete implementation of a Logistic Regression pipeline using the **Telco Customer Churn** dataset. The workflow includes data preprocessing, feature engineering, model training, and visualization of important concepts related to Logistic Regression.

The main objective is to build a binary classification model that predicts whether a customer is likely to leave the company (Churn) or remain a customer.

---

## Dataset

**Dataset:** Telco Customer Churn

The dataset contains customer demographic information, subscription details, and service usage records. The target variable is **Churn**, which has two classes:

- 0 → Customer stays
- 1 → Customer leaves

---

## Project Workflow

### 1. Import Libraries
Imported all required libraries for data manipulation, visualization, preprocessing, and machine learning.

### 2. Load Dataset
Loaded the dataset using Pandas and displayed the first records.

### 3. Data Exploration
- Dataset shape
- Dataset information
- Statistical summary
- Missing values
- Duplicate records

### 4. Data Cleaning
- Converted **TotalCharges** into numeric values.
- Filled missing values using the median.
- Removed the unnecessary **customerID** column.

### 5. Data Visualization
Visualized:
- Customer Churn distribution
- Feature distributions
- Probability distribution

### 6. Data Encoding
Converted categorical variables into numerical values using Label Encoding.

### 7. Feature Scaling
Standardized numerical features using StandardScaler.

### 8. Train-Test Split
Split the dataset into training and testing sets.

### 9. Logistic Regression Model
Built and trained a Logistic Regression classifier using Scikit-learn.

### 10. Custom Mathematical Functions
Implemented:
- Sigmoid Function
- Softmax Function
- Cross Entropy Loss

These functions help explain the mathematical concepts behind Logistic Regression.

### 11. Decision Boundary
Applied PCA to reduce the dataset into two dimensions and visualized the Logistic Regression decision boundary.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Results

The Logistic Regression model successfully learned patterns from the dataset and generated probability predictions for customer churn. Additional visualizations such as the Sigmoid curve, probability histogram, and decision boundary provide a better understanding of the model's behavior.

---

## Key Learning Outcomes

- Data preprocessing techniques
- Feature scaling
- Logistic Regression implementation
- Binary classification
- Sigmoid activation
- Cross Entropy Loss
- Decision Boundary visualization
- Machine Learning workflow
