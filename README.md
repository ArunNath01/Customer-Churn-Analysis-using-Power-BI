# Customer Churn Analysis using Power BI

## Overview

This project analyzes customer churn in a telecom company using **Power BI** to identify key factors influencing customer attrition and quantify its financial impact. The dashboard is designed for business executives and decision-makers to monitor churn performance, understand customer segments, and support data-driven retention strategies.

---

## Business Problem

Customer churn directly impacts revenue and customer acquisition costs. The objective of this project is to analyze customer behavior, identify high-risk customer segments, measure the financial impact of churn, and provide actionable business recommendations to improve customer retention.

---

## Objectives

* Measure overall customer churn performance.
* Identify customer segments with the highest churn.
* Analyze the relationship between contract type, internet service, tenure, and churn.
* Evaluate the financial impact of customer attrition.
* Present executive-level insights through an interactive Power BI dashboard.

---

## Dataset

The dataset contains customer demographic information, service details, billing information, and churn status.

### Features

| Column          | Description                                               |
| --------------- | --------------------------------------------------------- |
| customerID      | Unique customer identifier                                |
| gender          | Customer gender                                           |
| SeniorCitizen   | Indicates whether the customer is a senior citizen        |
| Partner         | Whether the customer has a partner                        |
| Dependents      | Whether the customer has dependents                       |
| tenure          | Number of months the customer has stayed with the company |
| InternetService | Internet service type                                     |
| Contract        | Customer contract type                                    |
| MonthlyCharges  | Monthly subscription charges                              |
| TotalCharges    | Total amount charged to the customer                      |
| Churn           | Indicates whether the customer left the company           |

---

## Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of business performance through key metrics and churn indicators.

**KPIs**

* Total Customers
* Churned Customers
* Churn Rate
* Total Revenue
* Revenue Lost

**Visualizations**

* Customer Status Distribution
* Churn by Contract Type
* Churn by Internet Service
* Churn by Tenure Group

---

### 2. Customer Segmentation

Analyzes churn across different customer groups.

**Visualizations**

* Churn by Gender
* Churn by Senior Citizen
* Churn by Partner Status
* Churn by Dependents
* Churn by Tenure Group

---

### 3. Financial Impact

Evaluates how customer churn affects business revenue.

**Visualizations**

* Revenue Lost by Contract Type
* Revenue Lost by Internet Service
* Average Monthly Charges by Churn
* Average Total Charges by Churn
* Top Revenue Lost Customers

---

## Key Performance Indicators (KPIs)

* Total Customers
* Churned Customers
* Churn Rate (%)
* Total Revenue
* Revenue Lost
* Average Monthly Charges
* Average Customer Revenue

---

## Data Preparation

The dataset was cleaned and transformed before analysis.

### Data Cleaning

* Corrected data types
* Converted `TotalCharges` to numeric
* Handled missing values
* Verified categorical values
* Created calculated columns

### Calculated Columns

* Churn Flag
* Senior Citizen Label
* Tenure Group
* Revenue

---

## Tools & Technologies

* Power BI Desktop
* Power Query
* DAX
* Microsoft Excel (Data Validation)
* Git & GitHub

---

## Business Insights

The dashboard enables stakeholders to:

* Monitor customer churn performance.
* Identify high-risk customer segments.
* Evaluate revenue loss associated with churn.
* Compare churn across contract types and internet services.
* Support customer retention strategies using data-driven insights.

---

## Business Recommendations

* Encourage customers to migrate from month-to-month contracts to longer-term contracts.
* Improve onboarding and engagement during the first year of the customer lifecycle.
* Develop targeted retention campaigns for high-value customers.
* Review pricing and service quality for customer groups with elevated churn.
* Monitor high-risk customer segments through regular executive reporting.

---

## Dashboard Preview

### Executive Overview


<img width="1692" height="791" alt="Screenshot 2026-07-06 010903" src="https://github.com/user-attachments/assets/21071b7d-2681-4495-9a45-8ebc29cb466c" />

### Customer Segmentation

<img width="1696" height="783" alt="Screenshot 2026-07-06 011039" src="https://github.com/user-attachments/assets/5dedd2b6-255f-4d7d-a12d-2fab920c4205" />


### Financial Impact
<img width="1706" height="790" alt="Screenshot 2026-07-06 011125" src="https://github.com/user-attachments/assets/7c78bd3a-5f41-49d7-b98f-8ab530521ae5" />


---

## Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling
* DAX Measures
* KPI Development
* Dashboard Design
* Business Intelligence
* Customer Analytics
* Executive Reporting
* Data Storytelling

---

## Future Improvements

* Integrate customer acquisition data to calculate retention metrics.
* Build a churn prediction model using machine learning.
* Connect the dashboard to a live SQL database.
* Add row-level security for department-specific reporting.

---

