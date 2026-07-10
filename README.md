# Customer Churn Analysis

## Background and Overview
### Business Problem
An insurance company has experienced increasing customer churn over the past year (YYYY=YYYY. Customer acquisition costs continue to rise, making customer retention a strategic priority. Management wants to understand which customers are leaving, why they are leaving, and what actions can reduce churn.

### Business Questions
1) What is the current customer churn rate?
2) How much revenue is being lost due to customer churn?
3) Which customer segments have the highest risk of churn? and which ones generate the highest customer lifetime value (CLV)?
4) What factors contribute to customer churn?
5) What actions could management take to reduce customer churn?

### Objectives
1) Measure the customer churn rate.
2) Estimate the revenue lost due to churn.
3) Identify customer segments carrying the highest churn risk and the highest lifetime value
4) Determine the leading indicators of churn.
5) Recommend strategies to improve customer retention.

#### Tools: [SQL](#) · [Python](#) · [Dashboard](#)

## Data Overview
Auto Insurance churn datasets provided by [Merishna Singh Suwal in Kaggle](https://www.kaggle.com/datasets/merishnasuwal/auto-insurance-churn-analysis-dataset)

It  consists of four distinct data files  as follows
1. address.csv: contains address information
2. customer.csv: contains customer information.
3. demographic.csv: contains demographic data
4. termination.csv: includes customer termination information.
The data set includes 2.2M customer records


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
-  Why are they leaving?
- Who's at risk?
[each: 1 chart + 2-3 sentence insight]

## Recommendations
| Recommendation  | Evidence | Impact |
| --------------- | ------------- |------------- |
| Encourage migration to annual contracts through targeted promotions or loyalty incentives.  | High churn among month-to-month customers  | Improve customer retention |
|Strengthen onboarding and customer engagement during the first three months. | High churn during early tenure  | Reduce early customer loss |
| Review pricing strategy and enhance value through bundled services or loyalty benefits. | High churn among higher-paying customers  | Increase customer satisfaction |


