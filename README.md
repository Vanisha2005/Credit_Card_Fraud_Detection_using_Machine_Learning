# Credit Card Fraud Detection using Machine Learning and Power BI

## Project Overview

This project presents an end-to-end approach to detecting fraudulent credit card transactions using Machine Learning and Business Intelligence. It covers the complete data analytics workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model development, and the creation of an interactive Power BI dashboard for business insights.

The objective is to identify fraud patterns, understand customer behavior, analyze key risk factors, and support data-driven decision-making through effective visualization.

---

## Objectives

* Analyze credit card transaction data to identify fraudulent activities.
* Perform data cleaning and preprocessing for reliable analysis.
* Conduct exploratory data analysis to uncover meaningful patterns.
* Build and evaluate a machine learning model for fraud detection.
* Develop an interactive Power BI dashboard to visualize business insights.
* Identify customer behavior and transaction characteristics associated with fraud.

---

## Dataset

The dataset contains approximately 10,000 credit card transaction records with features including:

* Transaction Amount
* Transaction Hour
* Merchant Category
* Cardholder Age
* Device Trust Score
* Transaction Velocity (Last 24 Hours)
* Foreign Transaction
* Location Mismatch
* Fraud Label (Target Variable)

---

## Project Workflow

```text
Data Collection
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Machine Learning Model
      ↓
Model Evaluation
      ↓
Power BI Dashboard
```

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Business Intelligence

* Power BI
* DAX (Data Analysis Expressions)

### Development Environment

* Jupyter Notebook

---

## Dashboard Overview

The Power BI dashboard is divided into three pages.

### 1. Executive Summary

Provides an overview of the dataset through key performance indicators such as:

* Total Transactions
* Fraud Cases
* Fraud Rate
* Total Transaction Amount
* Fraud Amount
* Average Transaction Amount

### 2. Fraud Pattern Analysis

Analyzes fraud trends using:

* Merchant Category Analysis
* Transaction Hour Analysis
* Fraud Distribution
* Transaction Amount Analysis
* Risk Trends

### 3. Customer Behavior and Risk Factors

Focuses on:

* Customer Age Groups
* Device Trust Score
* Transaction Velocity
* Foreign Transactions
* Location Mismatch
* Risk Categories
* Business Recommendations

---

## Key Insights

* Fraudulent transactions exhibit distinct behavioral patterns.
* Device trust score and transaction velocity are significant risk indicators.
* Certain merchant categories experience a higher concentration of fraudulent transactions.
* Foreign transactions and location mismatches are associated with increased fraud risk.
* Interactive dashboards enable faster identification of fraud trends and support informed business decisions.

---

## Repository Structure

```text
Credit-Card-Fraud-Detection/
│
├── Dataset/
│   └── credit_card_fraud_10k.csv
│
├── Notebook/
│   └── Credit_Card_Fraud_Detection.ipynb
│
├── Dashboard/
│   └── Credit_Card_Fraud_Dashboard.pbix
│
├── Images/
│   ├── Executive_Summary.png
│   ├── Fraud_Pattern_Analysis.png
│   └── Customer_Behavior_Risk_Factors.png
│
├── requirements.txt
└── README.md
```

---

## Future Enhancements

* Deploy the machine learning model as a web application.
* Integrate real-time transaction data.
* Compare multiple machine learning algorithms.
* Enhance the dashboard with real-time monitoring capabilities.
* Improve prediction accuracy through advanced feature engineering.

---

## Team Members

* Vanisha
* Divya Chauhan
* Sagar Shakya

---

## Acknowledgements

This project was completed as part of our Summer Training Program under the guidance of **Savleen Kaur Ma'am** and **Sandeep Kaur Ma'am**.

We sincerely thank our mentors and Lovely Professional University for their guidance, support, and the opportunity to work on an industry-oriented project that strengthened our practical knowledge of Data Science, Machine Learning, and Business Intelligence.

---

## License

This project is intended for educational and learning purposes.

