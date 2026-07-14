# 📊 SaaS Customer Churn & Subscription Analytics

An end-to-end Data Analytics project that analyzes customer subscriptions, product usage, support interactions, and churn behavior for a SaaS business. The project leverages **Python, SQL, Pandas, Matplotlib, and Seaborn** to perform data cleaning, feature engineering, exploratory data analysis (EDA), and business intelligence reporting.

---

## 📌 Project Overview

Customer retention is one of the most critical challenges for SaaS companies. This project analyzes customer behavior across multiple business dimensions—including subscriptions, feature usage, customer support, and churn events—to uncover actionable insights that can improve customer retention and revenue.

The analysis focuses on identifying churn patterns, customer engagement, revenue trends, support performance, and key business metrics that help drive strategic decision-making.

---

## 🎯 Objectives

- Analyze customer churn behavior and retention trends.
- Measure revenue performance using subscription data.
- Engineer business metrics such as Customer Tenure and Churn Risk.
- Evaluate product engagement through feature usage analytics.
- Analyze customer support performance and escalation trends.
- Identify the primary reasons behind customer churn.
- Generate business insights using data visualization and SQL.

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| Database | SQLite |
| Query Language | SQL |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Development | Jupyter Notebook |

---

## 📂 Dataset

The project uses **five relational datasets**.

| Dataset | Description | Records |
|---------|-------------|---------|
| Accounts | Customer profile information | 500 |
| Subscriptions | Subscription plans, billing, revenue, churn | 5,000 |
| Feature Usage | Product feature engagement | 25,000 |
| Support Tickets | Customer support interactions | 2,000 |
| Churn Events | Churn reasons, refunds, feedback | 600 |

---

# 📈 Project Workflow

### 1️⃣ Data Preparation

- Imported five relational datasets
- Created SQLite database
- Checked missing values
- Removed duplicates
- Validated primary keys
- Converted date columns
- Corrected data types

---

### 2️⃣ Feature Engineering

Created business metrics including:

- Customer Tenure
- Churn Score
- Churn Risk Classification
- Revenue at Risk
- Revenue Lost due to Churn

---

### 3️⃣ Exploratory Data Analysis

#### Customer Analytics

- Customer Churn Rate
- Retention Rate
- Churn by Subscription Plan
- Churn by Country
- Monthly Churn Trend
- Average Customer Tenure

#### Revenue Analytics

- Revenue by Subscription Plan
- Revenue by Country
- Average Revenue Per User (ARPU)
- Revenue Lost due to Churn

#### Product Analytics

- Top & Least Used Features
- Average Feature Usage Duration
- Feature Error Analysis
- Beta Feature Adoption
- Feature Usage Comparison (Active vs Churned Customers)

#### Support Analytics

- Ticket Priority Distribution
- Resolution Time Analysis
- First Response Time Analysis
- Customer Satisfaction Analysis
- Escalation Rate Analysis

#### Churn Event Analytics

- Top Churn Reasons
- Monthly Churn Trend
- Refund Analysis
- Refund by Churn Reason
- Reactivation Rate
- Customer Feedback Analysis

---

## 📊 Key Business KPIs

- Customer Churn Rate
- Customer Retention Rate
- Average Revenue Per User (ARPU)
- Revenue at Risk
- Revenue Lost due to Churn
- Average Customer Tenure
- Escalation Rate
- Average Complaint Rate
- Feature Adoption Rate
- Refund Amount
- Reactivation Rate

---

## 📉 Data Visualizations

The project includes multiple visualizations created using **Matplotlib** and **Seaborn**.

- 📌 Bar Charts
- 📌 Line Charts
- 📌 Pie Charts
- 📌 Heatmaps
- 📌 Correlation Matrix
- 📌 Catplots
- 📌 Pivot Tables

---

## 💾 SQL Analysis

SQLite was used to answer business questions such as:

- Customer Count
- Revenue Analysis
- Churn Analysis
- Revenue by Country
- Revenue by Subscription Plan
- Customer-Level Insights

---

## 📁 Project Structure

```text
SaaS-Customer-Churn-Analytics/
│
├── data/
│   ├── ravenstack_accounts.csv
│   ├── ravenstack_subscriptions.csv
│   ├── ravenstack_feature_usage.csv
│   ├── ravenstack_support_tickets.csv
│   └── ravenstack_churn_events.csv
│
├── notebooks/
│   └── SaaS_Customer_Churn_Analysis.ipynb
│
├── database/
│   └── customer_churn.db
│
├── images/
│   ├── churn_rate.png
│   ├── monthly_churn.png
│   ├── feature_usage.png
│   ├── support_analysis.png
│   └── correlation_heatmap.png
│
├── README.md
└── LICENSE
```

---

## 🔑 Key Insights

- Identified subscription plans with the highest customer churn.
- Measured revenue contribution across subscription plans and countries.
- Discovered the most and least adopted product features.
- Evaluated support performance using ticket priority, response time, and satisfaction metrics.
- Identified major churn reasons and associated refund costs.
- Engineered customer churn risk categories for business segmentation.

---

## 🚀 Future Enhancements

- Develop a machine learning model for churn prediction.
- Perform sentiment analysis on customer feedback.
- Automate reporting using Python.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL & SQLite
- Data Visualization
- Customer Churn Analysis
- Product Analytics
- Support Analytics
- KPI Development
- Business Intelligence
- Business Insight Generation

---

## 🤝 Connect With Me

If you found this project helpful or have suggestions, feel free to connect with me on **LinkedIn** or explore more of my projects on **GitHub**.

⭐ If you like this project, consider giving it a star!
