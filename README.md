# 📊 Customer Churn Analysis Dashboard | Power BI

An interactive Power BI dashboard designed to analyze customer churn, retention patterns, contract types, tenure, and monthly charges.

The dashboard provides an overview of customer churn behavior and helps identify customer segments that are more likely to churn.

---

## 📌 Project Overview

Customer churn is an important business metric because losing existing customers can significantly impact revenue and long-term growth.

This project uses Power BI to analyze customer-level data and transform it into an interactive dashboard that provides insights into:

- Overall customer churn
- Churn rate
- Retained vs churned customers
- Customer risk segments
- Contract types associated with churn
- Customer tenure and churn behavior
- Monthly charges of retained and churned customers
- Online security and online backup service patterns

---

## 🎯 Objectives

The main objectives of this project are:

- Calculate and visualize the overall churn rate
- Identify customer segments with higher churn risk
- Analyze churn across different contract types
- Understand the relationship between customer tenure and churn
- Compare monthly charges between retained and churned customers
- Analyze customer retention based on additional services
- Create an interactive dashboard for business decision-making

---

## 📊 Dashboard Overview

The dashboard contains several key visualizations:

### KPI Cards

- Total Customers: **7,043**
- Churn Rate: **26.54%**
- Churned Customers: **1,869**

### Customer Risk Analysis

The dashboard categorizes retained customers into risk types and provides an overview of customers classified as:

- Normal Risk
- High Risk

### Churn by Contract Type

The analysis shows that **Month-to-Month customers have significantly higher churn** compared with customers on one-year and two-year contracts.

### Customer Tenure Analysis

Customers with shorter tenure show a considerably higher churn rate.

The dashboard analyzes three tenure groups:

- 0–6 Months
- 6–12 Months
- 12+ Months

### Monthly Charges Analysis

The dashboard compares average monthly charges between retained and churned customers.

### Online Services Analysis

Monthly charges are analyzed based on services such as:

- Online Security
- Online Backup
- No Internet Service

---

## 🔍 Key Insights

Some of the major insights identified from the dashboard include:

1. **Overall churn rate is 26.54%**, meaning more than one-fourth of the analyzed customers have churned.

2. **Month-to-Month contract customers represent the largest churn segment**, with 1,655 churned customers.

3. **Customers with shorter tenure have higher churn rates.** The 0–6 month segment has a churn rate of approximately 52.94%.

4. Customers with **12+ months of tenure have a much lower churn rate**, approximately 17.13%.

5. The analysis highlights differences in **monthly charges between retained and churned customers**, which can help identify pricing-related churn patterns.

6. Additional services such as **Online Security and Online Backup** can be analyzed to understand their relationship with customer retention.

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures, calculated columns, and KPI calculations
- **Excel/CSV** – Data source and preprocessing

---

## 📊 Dashboard Preview

![Customer Churn Dashboard](Images/Dashboard.png)

---

## 📂 Project Structure

```text
customer-churn-analysis-powerbi/
│
├── Dashboard/
│   └── Customer_Churn_Dashboard.pbix
│
├── Images/
│   └── customer-churn-dashboard.png
│
├── Dataset/
│   └── customer_churn.csv
│
└── README.md
