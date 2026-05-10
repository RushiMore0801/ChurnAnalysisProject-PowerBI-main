# Customer Churn Analysis & Prediction Dashboard

## Project Overview
This project focuses on analyzing and predicting **customer churn** in the telecom industry using Machine Learning and visualizing insights through a **Power BI Dashboard**.

Customer churn means when customers leave a company’s service and switch to another provider.

## Aim of the Project
In telecom, acquiring new customers is expensive, while retaining existing customers is cheaper.

👉 This project helps:
- Predict which customers are likely to leave
- Enable companies to take early actions (offers, retention strategies)

## Problem Statement
High customer churn leads to revenue loss.

Traditional analysis cannot accurately identify customers at risk.

👉 Solution:
Use **data analysis + machine learning models** to predict churn in advance.

## Dataset & EDA (Exploratory Data Analysis)

### Dataset:
- Telco Customer Churn Dataset

### EDA Includes:
- Understanding customer demographics
- Analyzing service usage
- Contract types & tenure
- Billing patterns

### Benefits:
- Detect missing values
- Identify outliers
- Understand feature relationship

## Data Cleaning & Preprocessing

Steps performed:
- Handled missing values
- Removed duplicates
- Converted categorical data into numeric (Encoding)
- Applied feature scaling

## Feature Engineering

Created new features for better prediction:

### Example:
- Customer Tenure Groups:
  - 0–12 months → New customers
  - 1–3 years → Mid-term
  - 3+ years → Loyal customers

👉 Helps model understand behavior patterns better

## Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Deep Learning (Neural Network)

### Why Multiple Models?
To compare performance and select the best model.

## Model Evaluation

- Problem Type: Classification (Yes / No)

### Key Metric:
- Recall (Important because missing churn customers is costly)

## Power BI Dashboard

After prediction, results are visualized using Power BI.

### Dashboard Features:
- Churn distribution
- Customer segmentation
- Service usage insights
- Interactive filters

👉 Helps non-technical users understand insights easily

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Deep Learning (Neural Network)
- Power BI
- Jupyter Notebook

## 📂 Project Structure
├── Churn Analysis - EDA.ipynb
├── Telco-Customer-Churn.csv
├── Telecom-Churn-Analysis-Dashboard.pbix
├── Exploratory Data Analysis.pdf
├── Business Understanding.pdf
