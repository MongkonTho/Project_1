# Olist Marketplace Performance Analysis

## Background and Overview
### Business Problem
Olist is a Brazilian e-commerce marketplace that connects customers with thousands of independent sellers across Brazil. After several years of operation, the executive team wants to evaluate the marketplace's performance between 2016 and 2018 to identify opportunities for sustainable growth and operational improvement. 

Although Olist has experienced steady marketplace growth, management lacks a comprehensive view of business performance across multiple domains, including sales, customers, logistics, and sellers. Without these insights, it is difficult to identify growth opportunities, improve customer experience, and prioritize operational improvements.

#### Business Questions
**How can Olist achieve sustainable revenue growth by improving customer retention, seller performance, and delivery experience?** This overarching question is broken down into four sub-domains as follows;

1) **Sales performance**: How is the business performing and what drives revenue?
2) **Customer analytics**: Who are the most valuable customers and how can retention be improved?
3) **Operational excellence**: Where are delivery inefficiencies and how do they affect the customer experience?
4) **Marketplace performance**: Which sellers and product categories drive success and which require intervention?

### Objectives
This project aims to analyze Olist's marketplace performance from four business domains to generate actionable recommendations for management:
1) Evaluate sales performance and revenue drivers.
2) Understand customer purchasing behavior and retention.
3) Assess delivery performance and operational efficiency.
4) Identify high-performing sellers and product categories.

#### Tools
This project demonstrates an end-to-end data analytics workflow using:

- **[SQL](#)**: Data extraction, cleaning, joins, KPI calculations
- **[Python](#)**: Exploratory data analysis and visualization
- **[Tableau](#)**: Interactive executive dashboard

## Data Overview
This project uses the Brazilian E-Commerce Public Dataset provided by [Olist on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). The dataset contains approximately:
- Nine relational tables covering orders, customers, products, sellers, payments, logistics, reviews, and geolocation between 2016 and 2018.
- 100,000 orders
- 96,000 customers
- Thousands of sellers
- Multiple product categories




| Metric  | Value |
| ------------- | ------------- |
| Number of records  | 7,043  |
|Number of variables  | 21  |
|Missing values  | 21  |

Data Model
(Insert Entity Relationship Diagram here.)

## Executive Summary
OVERVIEW:
Customer churn is primarily concentrated among customers with month-to-month contracts, shorter customer tenure, and higher monthly charges. In contrast, customers on long-term contracts exhibit substantially higher retention.

These findings suggest that customer retention strategies should prioritize early customer engagement and encourage migration toward longer-term subscription plans.

(Insert dashboard overview image here.)

## Insights Deep-Dive
- Who is leaving?
- Why are they leaving?
- Who's at risk?
[each: 1 chart + 2-3 sentence insight]

## Recommendations
| Recommendation  | Evidence | Impact |
| --------------- | ------------- |------------- |
| Encourage migration to annual contracts through targeted promotions or loyalty incentives.  | High churn among month-to-month customers  | Improve customer retention |
|Strengthen onboarding and customer engagement during the first three months. | High churn during early tenure  | Reduce early customer loss |
| Review pricing strategy and enhance value through bundled services or loyalty benefits. | High churn among higher-paying customers  | Increase customer satisfaction |


