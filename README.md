# Customer Churn Analysis & Retention Dashboard

## Project Overview
This project focuses on analyzing telecom customer churn behavior using Python, SQL, Power BI, and basic Machine Learning concepts. The objective of the project is to identify customer retention patterns, understand factors influencing churn, and provide business-driven insights through an interactive dashboard.

The project includes:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Customer Risk Segmentation
- Interactive Power BI Dashboard
- SQL-Based Analysis
- Machine Learning Churn Prediction Model

---

# Business Problem
Telecom companies face significant customer loss due to churn. Retaining customers is more cost-effective than acquiring new customers. This project helps identify:
- Customers likely to churn
- High-risk customer segments
- Contract types contributing to churn
- Revenue impact of churn behavior

---

# Tools & Technologies Used

## Programming & Analytics
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dashboarding
- Power BI

## Database & Querying
- SQL

## Machine Learning
- Scikit-learn
- Logistic Regression

---

# Dataset Information

The dataset contains telecom customer information including:
- Customer demographics
- Contract details
- Monthly charges
- Internet services
- Payment methods
- Customer tenure
- Churn status

---

# Project Workflow

## 1. Data Cleaning & Preprocessing
- Removed unnecessary columns
- Handled missing values
- Converted data types
- Created customer risk segmentation

## 2. Exploratory Data Analysis
Performed analysis on:
- Churn distribution
- Contract impact
- Monthly charges
- Internet service types
- Customer tenure
- Payment methods

## 3. Risk Segmentation
Customers were categorized into:
- High Risk
- Medium Risk
- Low Risk

based on customer tenure behavior.

## 4. Machine Learning Model
Implemented Logistic Regression model for churn prediction:
- Label Encoding
- Feature Scaling
- Train-Test Split
- Model Training
- Prediction & Accuracy Evaluation

## 5. Power BI Dashboard
Created an interactive dashboard with:
- KPI Cards
- Contract Analysis
- Churn Trend Analysis
- Risk Segmentation
- Payment Method Analysis
- Interactive Slicers

---

# Dashboard Features

## KPI Metrics
- Total Customers
- Churned Customers
- Churn Rate %
- Average Monthly Revenue
- Average Tenure
- High-Risk Customers

## Visual Insights
- Month-to-month customers show highest churn
- Short-tenure customers are more likely to churn
- Fiber optic users exhibit higher churn
- Higher monthly charges drive churn
- Customer churn varies across payment methods

---

# Machine Learning Highlights

## ML Algorithm Used
- Logistic Regression

## ML Workflow
- Data Encoding
- Feature Scaling
- Model Training
- Prediction
- Accuracy Evaluation

## Purpose of ML
The ML model predicts whether a customer is likely to churn based on customer behavior patterns.

---

# Project Structure

```text
Customer-Churn-Analysis
│
├── FINAL_DASHBOARD_DATA.csv
├── customer_churn_dashboard.pbix
├── Customer_Churn_Analysis.ipynb
├── Customer_Churn_ML_Model.ipynb
├── SQL_Queries.sql
├── README.md
└── screenshots
    └── dashboard.png
