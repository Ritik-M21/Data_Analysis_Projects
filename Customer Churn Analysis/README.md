# Customer Churn Analysis Dashboard

## Introduction
Customer churn refers to the percentage of customers who stop using a company’s product or service during a given time period. Analyzing churn is crucial for businesses because acquiring new customers is often more expensive than retaining existing ones. This project focuses on analyzing customer churn data using SQL for data cleaning and transformation, and Power BI for creating an interactive dashboard that highlights key trends, risk factors, and business insights.

## Problem Statement
Companies in subscription-based or service-oriented industries face a major challenge: customer attrition (churn). Without identifying the reasons behind churn, businesses lose revenue and market share.
Key business questions:
- What percentage of customers are churning?
- Which customer segments (by contract, tenure, payment method, demographics) are at higher risk of churn?
- What are the main factors contributing to customer churn?
- How can business stakeholders monitor churn trends in real-time?

## Tech Stack
- **SQL** (MySQL) → Data Cleaning, Transformation, Aggregations
- **Power BI** → Dashboard creation & visualization
- **Excel/CSV** → Kaggle

## Objectives
- Clean and prepare raw customer data using SQL.
- Build interactive Power BI dashboards to visualize churn metrics.
- Provide actionable insights that help reduce churn and improve customer retention.

## Data Cleaning and EDA
Checkong null values
![image](https://github.com/Ritik-M21/Data_Analysis_Projects/blob/main/Customer%20Churn%20Analysis/SQL%20file/checking%20null.png?raw=true)

## Key Performance Indicators (KPIs)
- Total Customers
- New Joiners
- Total Churn
- Churn Rate

## Dashboard
![image](https://github.com/Ritik-M21/Data_Analysis_Projects/blob/main/Customer%20Churn%20Analysis/Dashboard.png?raw=true)

## Insights
- Total churn for female(1111) was higher than male(621).
- Above 50 age group accounted fro 42% of total customer.
- Total customers and churn rate diverged the most when the tenure group was >=24 months when customers were 2087 higher than churn rate.
- Major churn caused due to price range between 50-100 and better services provided by competitors 
- In case of provided services, unlimited data services has highest churn rate of 80% while device protection plan has lowest churn rate of 28%. 
