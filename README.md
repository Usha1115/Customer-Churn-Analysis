# Customer Churn Analysis

## 📊 Project Overview

Customer churn analysis project focused on understanding customer retention patterns and identifying factors associated with customer churn.
The analysis was performed using **Excel and Power BI** on a dataset containing **10,000 customer records**.

---

## 🎯 Business Objective

- Measure the overall customer churn rate
- Compare churn across different customer segments
- Understand customer tenure and spending patterns
- Identify areas where customer retention can be improved
- Provide data-driven insights for retention strategies

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
  - Data Cleaning
  - Data Preparation
  - Pivot Tables
  - Calculations

- **Power BI**
  - Data Visualization
  - DAX Measures
  - Interactive Dashboard
  - Slicers & Filters

---

## 📌 Key KPIs

| KPI | Value |
|---|---:|
| Total Customers | 10,000 |
| Churned Customers | 2,670 |
| Overall Churn Rate | 26.70% |
| Average Tenure | 35.96 Months |

---

## 📈 Dashboard Analysis

### Customer Overview

The first dashboard provides an overview of customer churn across:

- Contract type
- Tenure groups
- Payment methods
- Overall churn status

![Customer Overview](Screenshots/Customer_Overview.png)

---

### Customer Retention Analysis

The second dashboard analyzes:

- Average tenure of churned vs. retained customers
- Average monthly charges
- Average total charges
- Churn rate among senior and non-senior customers

![Customer Retention Analysis](Screenshots/Customer_Retention_Analysis.png)

---

## 🔍 Key Insights

- Overall customer churn rate was **26.70%**.
- Churn patterns were analyzed across contract type, tenure, payment method and customer demographics.
- Average monthly charges were very similar between churned and retained customers.
- Average tenure was also relatively similar between churned and retained customers.
- The analysis suggests that customer retention should be evaluated using multiple behavioral and demographic factors rather than relying on a single variable.

---

## 💡 Business Recommendations

- Monitor customer segments with comparatively higher churn rates.
- Develop targeted retention campaigns for at-risk customers.
- Analyze customer behavior over time to identify early churn signals.
- Use contract and payment-method patterns to personalize retention strategies.
- Continuously monitor churn KPIs through an interactive dashboard.

---

## 📂 Repository Structure

```text
Customer-Churn-Analysis/
│
├── Customer_Churn_Analysis.pbix
├── Customer_Churn_Cleaned.xlsx
├── Customer_Overview.png
├── Customer_Retention_Analysis.png
└── README.md
