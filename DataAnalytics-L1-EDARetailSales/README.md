# Exploratory Data Analysis (EDA) on Retail Sales Data

## Oasis Infobyte — Data Analytics Internship

**Domain:** Data Analytics  
**Level:** 1  
**Task:** 1  
**Project:** Retail Sales Exploratory Data Analysis  
**Author:** Abhishek Sapre

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset using Python. The objective is to understand sales performance, identify customer purchasing patterns, analyze profitability, and generate actionable business insights.

The primary Superstore dataset contains **10,194 records and 21 columns**.

## Objectives

- Understand the structure and quality of retail sales data.
- Identify missing values and duplicate records.
- Analyze sales and profit across product categories.
- Explore monthly and quarterly sales trends.
- Identify the top 10 best-selling products.
- Analyze customer segments and purchasing patterns.
- Study correlations between numerical variables.
- Provide business recommendations based on findings.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Information

### Primary Dataset: Superstore Retail Sales

The dataset includes:

- Order ID and Order Date
- Customer ID and Customer Name
- Customer Segment
- Country, City and Region
- Product Category and Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

### Supplementary Dataset: E-Commerce Customer Behavior

A separate e-commerce dataset is used to explore customer demographics, including age and gender.

**Note:** The demographic analysis uses a different dataset and is not directly linked to the Superstore sales records.

## Exploratory Data Analysis

### 1. Data Understanding and Cleaning

- Loaded the retail dataset using Pandas.
- Examined dataset dimensions and column names.
- Checked missing values.
- Inspected numerical and categorical variables.
- Prepared date columns for time-series analysis.

### 2. Sales Analysis

Analyzed total sales across Technology, Furniture and Office Supplies.

**Finding:** Technology generated the highest sales among the three categories.

### 3. Profitability Analysis

Calculated total profit and profit margins by product category.

| Category | Total Sales | Total Profit | Profit Margin |
|---|---:|---:|---:|
| Technology | 839,893.28 | 146,543.38 | 17.45% |
| Office Supplies | 731,893.31 | 126,023.44 | 17.22% |
| Furniture | 754,747.76 | 19,730.00 | 2.61% |

**Finding:** Furniture had the lowest profit margin, indicating an opportunity to improve profitability.

### 4. Monthly and Quarterly Sales Trends

Analyzed changes in retail sales over time using line charts to identify sales patterns and periods of stronger performance.

### 5. Top 10 Best-Selling Products

Identified the highest-selling products based on total quantity sold.

This analysis helps identify products with strong customer demand.

### 6. Customer Segment Analysis

Examined sales performance across customer segments to understand purchasing patterns.

### 7. Correlation Analysis

Generated a correlation heatmap for numerical variables.

**Key observations:**

- Sales and Profit correlation: **0.48**
- Discount and Profit correlation: **-0.22**

These findings indicate a moderate positive relationship between sales and profit and a weak negative relationship between discount and profit.

Correlation does not establish causation.

### 8. Customer Demographic Analysis

Used a supplementary e-commerce dataset to explore:

- Customer age distribution
- Customer gender distribution

Visualized the results using histograms and bar charts.

## Key Findings

1. Technology generated the highest total sales and profit.
2. Furniture had the lowest profit margin at 2.61%.
3. Sales and profit showed a moderate positive correlation.
4. Discounts and profit showed a weak negative correlation.
5. Customer demographic distributions were explored using supplementary e-commerce data.

## Business Recommendations

1. **Prioritize high-performing categories:** Maintain strong inventory availability and product selection for Technology products.

2. **Improve Furniture profitability:** Review discounts, product costs and low-margin items to identify opportunities for improvement.

3. **Monitor Office Supplies performance:** Maintain sales momentum while tracking profit margins and customer demand.

## Project Files

- `Retail_Sales_EDA Final.ipynb` — Python notebook containing data analysis, visualizations and conclusions.
- `README.md` — Project overview, methodology, findings and recommendations.

## Conclusion

This project demonstrates practical skills in data cleaning, exploratory data analysis, data visualization and business insight generation using Python.

The analysis highlights category-level sales performance, profitability differences, customer purchasing patterns and opportunities for business improvement.

**Internship:** Oasis Infobyte  
**Domain:** Data Analytics  
**Level:** 1 — Task 1
