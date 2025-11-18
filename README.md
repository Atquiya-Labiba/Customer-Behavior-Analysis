# Customer-Behavior-Analysis
## Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.
## Dataset Summary
- Rows: 3,900
- Columns: 18
- Key Features: 
- Customer demographics (Age, Gender, Location, Subscription Status)
-  Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)
-  Shopping behavior (Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type)
-  Missing Data: 37 values in Review Rating column

## Data Analysis with Python
- Handled missing values by imputing review ratings using category-wise medians and preparing age-based segments using quantile grouping
- Feature Engineering to create new columns
- Visualized customer demographics

## PostgreSQL
- Performed SQL analysis including customer segmentation queries, category-wise purchase trends, gender & location distributions, and frequency-based customer behavior exploration.
## Power BI
-Built interactive Power BI dashboards to visualize patterns
Findings:
- Higher number of customers without subscription status
- Clothing category and Young adult group has higher revenue and sales
- Outwear category and Adult, Senior has lowest revenue and sales
