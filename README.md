# Olist Marketplace Performance Analysis

## Background and Overview
### Business Problem
Olist is a Brazilian e-commerce marketplace that connects customers with thousands of independent sellers across Brazil. After several years of operation, the executive team wants to evaluate the marketplace's performance between 2016 and 2018 to identify opportunities for sustainable growth and operational improvement. 

Although Olist has experienced steady marketplace growth, management lacks a comprehensive view of business performance across multiple domains, including sales, customers, logistics, and sellers. Without these insights, it is difficult to identify growth opportunities, improve customer experience, and prioritize operational improvements.

#### Business Questions
***How can Olist achieve sustainable revenue growth by improving customer retention, seller performance, and delivery experience?*** This overarching question is broken down into four sub-domains as follows;

1) ***Sales performance***: How is the business performing and what drives revenue?
2) ***Customer analytics***: Who are the most valuable customers and how can retention be improved?
3) ***Operational excellence***: Where are delivery inefficiencies and how do they affect the customer experience?
4) ***Marketplace performance***: Which sellers and product categories drive success and which require intervention?

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

Data Model
(Insert Entity Relationship Diagram here.)

## Executive Summary: Business insights
### Sales
- Revenue increased by XX% between 2016 and 2018, supported by higher order volumes and increased average order value.
- Growth was primarily driven by Category A, Category B, and Category C.
### Customer
- Customers in the High-Value segment accounted for XX% of total revenue and exhibited the highest repeat purchase rate.
- Low-value customers were concentrated in Region A and Region B, with limited repeat purchasing.
### Operaiton
- Average delivery time was XX days and improved/deteriorated over the study period.
- XX% of orders were delivered later than the estimated date, with delays concentrated in State A, State B, and State C.
### Seller 
- The top-performing sellers were concentrated in the XXX product category and YYY state, consistently maintaining high customer ratings.
- Revenue was highly concentrated among a relatively small proportion of sellers, indicating dependency on key marketplace partners.

*The insights are based on these following planned analyses*

| Domain   | Planned Analyses |
|----------|---------|
| Sales    | Revenue trend |
|          | Order trend |
|          | Average order value |
|          | Top product category |
| Customer | Repeat purchase rate |
|          | RFM segment |
|          | Geographical distribution |
|          | Customer value |
| Operation | Delivery time |
|          | Late delivery share |
|          | Freigth cost |
|          | Performance by state |
| Seller   | Top seller |
|          | Seeler concentration |
|          | Seller rating |
|          | production performance|

Executive Dashboard


## Recommendations
### Sales
- Increase marketing investment in these high-growth categories while identifying opportunities to improve underperforming categories.
### Customer
- Develop targeted retention campaigns for high-value customers and personalized promotions for low-value segments.
### Operaiton
- Prioritize logistics improvements in these regions and collaborate with sellers experiencing persistent delays.
### Seller 
- Support high-performing sellers while providing operational guidance to lower-performing sellers to reduce concentration risk.

