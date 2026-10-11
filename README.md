# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using Python, MySQL, and Power BI. It explores purchasing patterns, product ratings, discount usage, customer segments, and subscription behavior to identify insights that can support business decisions.

The dataset contains 3,900 records and 18 original columns.

## Business Problem

The objective is to understand customer shopping patterns, improve customer engagement, and identify opportunities to optimize marketing and product strategies.

## Project Objectives

- Analyze purchase amounts across customer groups.
- Identify products with high average review ratings.
- Compare purchasing patterns across shipping types.
- Analyze subscription status and customer spending.
- Examine discount usage across products.
- Segment customers based on previous purchases.
- Explore revenue patterns across age groups.

## Tools and Technologies

- Python
- Pandas
- NumPy
- MySQL
- SQL
- Power BI
- Jupyter Notebook

## Project Workflow

### 1. Data Cleaning and Preparation

- Loaded and explored the dataset using Pandas.
- Identified missing values in the review rating column.
- Imputed missing review ratings using category-wise median values.
- Standardized column names.
- Created age groups and purchase frequency features.
- Checked consistency between discount and promo-code columns.

### 2. SQL Analysis

Used MySQL to answer business questions involving:

- Revenue by gender.
- High-spending customers who used discounts.
- Top-rated products.
- Average purchase amounts by shipping type.
- Subscriber and non-subscriber spending.
- Product discount rates.
- Customer segmentation.
- Top products within each category.
- Repeat buyers and subscription status.
- Revenue by age group.

### 3. Power BI Dashboard

Created an interactive dashboard with key performance indicators and visualizations to explore customer spending, product categories, age groups, and subscription behavior.

Filters allow users to explore the data by selected customer and shopping attributes.

## Key Findings

- Gloves had the highest average review rating among the five highest-rated products, at 3.86.
- Express shipping had an average purchase amount of $60.48, compared with $58.46 for Standard shipping.
- Hats had the highest discount-application rate among the products analyzed, at 50%.
- Non-subscribers generated higher total recorded purchase revenue than subscribers in this dataset.

## Project Files

- `Business Problem Statement.pdf` - Business problem and project objectives.
- `Business_Questions.sql` - SQL business analysis queries.
- `customer_shopping_behavior.csv` - Dataset.
- `Customer_Shopping_Behavior_Analysis.ipynb` - Python analysis notebook.
- `Customer_Behavior_Dashboard.pbix` - Power BI dashboard file.
- `Final_Dashboard.png` - Dashboard preview.
- `Customer_Shopping_Behavior_Analysis_Report.pdf` - Project report.
- `Customer_Shopping_Behavior_Professional_Presentation.pptx` - Project presentation.

## Conclusion

This project demonstrates a complete data analytics workflow, from data preparation and SQL-based analysis to interactive dashboard development and business reporting.

The findings provide a starting point for exploring customer behavior and identifying opportunities for further analysis.
