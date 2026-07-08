# FinTech Revenue and Fraud Analytics

## Project Overview

FinTech Revenue and Fraud Analytics is an end-to-end Business Intelligence project designed to analyze financial transaction data, identify revenue trends, understand customer spending behavior, and uncover fraud patterns. The project combines Python-based data analysis with interactive Power BI dashboards to deliver actionable business insights.

The objective of this project is to help financial institutions and FinTech companies monitor transaction performance, analyze customer segments, and identify high-risk fraud categories through data-driven decision making.

---

## Business Problem

Financial institutions process thousands of transactions daily, making it challenging to:

- Track revenue performance effectively
- Understand customer spending behavior
- Identify high-value customer segments
- Detect fraudulent transaction patterns
- Monitor fraud-prone categories and regions

This project addresses these challenges by building a comprehensive analytics solution using Python and Power BI.

---

## Dataset Information

The dataset contains credit card transaction records with customer, merchant, geographic, and transaction-related information.

### Key Features

- Transaction Amount
- Transaction Date and Time
- Customer Information
- Merchant Category
- Customer Location
- Occupation
- Fraud Label
- Demographic Information

---

## Technology Stack

### Programming & Analytics

- Python
- Pandas
- NumPy
- Matplotlib

### Business Intelligence

- Power BI
- DAX

### Development Environment

- Google Colab
- GitHub

---

## Project Workflow

### 1. Data Audit

Performed an initial assessment of the dataset to understand:

- Dataset structure
- Missing values
- Data types
- Data quality issues
- Business KPIs

### 2. Data Cleaning & Feature Engineering

Created new analytical features including:

- Age
- Age Group
- Customer Name
- Revenue Segments
- Year
- Month
- Day
- Hour

### 3. Exploratory Data Analysis

Analyzed:

- Revenue trends
- Customer demographics
- Geographic performance
- Occupation-based spending
- Category-wise revenue
- Fraud distribution

### 4. Business Intelligence Dashboard

Developed a multi-page Power BI dashboard to provide executive, customer, and fraud analytics insights.

---

# Dashboard Pages

## Executive Financial Overview

### KPIs

- Total Revenue
- Total Transactions
- Fraud Transactions
- Fraud Rate
- Average Transaction Value

### Visualizations

- Monthly Revenue Trend
- Revenue by Category
- Revenue by Customer Segment

---

## Customer & Market Insights

### Visualizations

- Revenue by State
- Revenue by Age Group
- Revenue by Gender
- Revenue by Occupation

### Insights

- Top revenue-generating states
- High-value age groups
- Gender-wise spending contribution
- Occupation-based spending patterns

---

## Fraud Risk Analytics

### Visualizations

- Fraud Transactions by Category
- Fraud vs Non-Fraud Distribution
- Fraud Transactions by Age Group
- Fraud Transactions by State

### Insights

- High-risk transaction categories
- Fraud concentration by geography
- Fraud-prone customer segments
- Overall fraud exposure

---

## Key Findings

### Revenue Insights

- Total Revenue exceeded 7 million.
- Grocery and shopping categories generated the highest revenue.
- New York and Texas were among the top revenue-generating states.

### Customer Insights

- Customers aged 36–55 contributed significantly to total revenue.
- Female customers generated slightly higher revenue compared to male customers.
- Certain occupations showed consistently higher transaction volumes.

### Fraud Insights

- Grocery POS and Shopping Net categories recorded the highest fraud activity.
- Fraud transactions represented less than 1% of total transactions.
- Fraud occurrences were concentrated in specific states and customer segments.

---

## Project Structure

```text
FinTech-Revenue-and-Fraud-Analytics/

├── data/
│   └── fintech_cleaned.csv
│
├── notebooks/
│   ├── 01_Data_Audit.ipynb
│   ├── 02_Data_Cleaning_Feature_Engineering.ipynb
│   └── 03_Exploratory_Data_Analysis.ipynb
│
├── dashboard/
│   └── FinTech_Business_Intelligence_Dashboard.pbix
│
├── Images/
│   ├── executive_financial_overview.png
│   ├── customer_market_insights.png
│   └── fraud_risk_analytics.png
└── README.md
```

---

## Dashboard Screenshots

### Executive Financial Overview
executive_financial_overview.png


### Customer & Market Insights

customer_market_insights.png

### Fraud Risk Analytics

fraud_risk_analytics.png

---

## Future Enhancements

- Machine Learning based Fraud Detection
- Real-Time Transaction Monitoring
- Customer Risk Scoring
- Predictive Revenue Forecasting
- Advanced Fraud Alert System

---

## Author

**M Siri Vennela**

B.Tech – Computer and Communication Engineering

Amrita Vishwa Vidyapeetham, Chennai

GitHub: https://github.com/sirivennelamalli
