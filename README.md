# Airline Profit Prediction Model

## Overview
This project builds a **machine learning model** to predict airline profitability and optimize operations.

## Steps to Build the Model

### **Step 1: Dataset Overview**
- Data includes key airline operational and financial metrics like **flight delays, aircraft utilization, fuel efficiency, revenue, and costs**.
- The dataset is loaded from a CSV file.

### **Step 2: Data Preprocessing**
- **Handling Missing Values:** Remove rows with null values.
- **Feature Engineering:** Convert percentage-based features to decimal format.
- **Creating Profit per ASK:** A new profitability metric.
- **Outlier Removal:** Using **Interquartile Range (IQR)** to filter extreme values.
- **Feature Scaling:** Normalized using **MinMaxScaler**.

### **Step 3: Splitting Data for Model Training**
- Data is split into **80% training and 20% testing sets**.

### **Step 4: Machine Learning Model Training**
- Models tested:
  - **Linear Regression**
  - **Ridge Regression**
  - **Random Forest**
  - **Gradient Boosting**
  - **AdaBoost**
  - **Support Vector Regression (SVR)**
  - **K-Nearest Neighbors (KNN)**

### **Step 5: Model Evaluation Metrics**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Percentage Error (MAPE)**
- **R² Score**

### **Step 6: Selecting the Best Model**
- The model with the **highest R² Score** is chosen as the best predictor.
- Prints evaluation metrics for comparison.

## **Installation & Usage**
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
   ```
2. Run the script to train models and identify the best one.

## **Future Improvements**
- Hyperparameter tuning.
- Adding external factors like fuel prices.
- Exploring deep learning models.


