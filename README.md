# 🛒 E-commerce Sales Analysis

## 📌 Project Overview

This project analyzes e-commerce sales data to identify sales trends, profitable products, customer purchasing patterns, and factors affecting business profitability.

The analysis was performed using Python, Pandas, Matplotlib, and Seaborn.

## 🎯 Business Objectives

- Analyze overall sales and profitability
- Identify high-performing categories and products
- Analyze sales by city
- Compare payment methods and sales channels
- Understand the impact of discounts on profit
- Identify loss-making orders
- Analyze relationships between revenue, cost, and profit
- Generate actionable business recommendations

## 📊 Dataset

The dataset contains e-commerce order-level information including:

- Order ID
- Order Date
- Customer ID
- City
- Category
- Product
- Quantity
- Unit Price
- Payment Method
- Sales Channel
- Discount Percentage
- Revenue
- Cost
- Profit

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Analysis Performed

### Data Understanding
- Dataset structure and dimensions
- Data types
- Missing-value analysis
- Duplicate-value analysis
- Descriptive statistics

### Exploratory Data Analysis
- Revenue distribution
- Profit distribution
- Outlier detection
- Monthly revenue analysis
- Monthly profit analysis
- Category analysis
- City analysis
- Product analysis
- Payment method analysis
- Sales channel analysis
- Discount analysis

### Profitability Analysis
- Discount vs Profit
- Loss-making orders
- Revenue vs Profit
- Correlation analysis
- Data validation

## 📈 Key Findings

- Revenue shows a right-skewed distribution with a small number of high-value orders.
- Profit varies significantly across orders, including some loss-making orders.
- Revenue and profit have a strong positive correlation.
- Revenue and cost have an extremely strong positive relationship.
- Higher discounts show a negative relationship with profit.
- High-revenue orders should also be evaluated based on profitability rather than revenue alone.

## 💡 Business Recommendations

1. Monitor high-discount orders to protect profit margins.
2. Focus on products and categories that generate strong profit.
3. Investigate loss-making orders to identify pricing or cost issues.
4. Monitor high-revenue but low-profit orders.
5. Analyze high-cost products and identify opportunities to improve margins.
6. Use city and sales-channel performance to improve marketing and sales strategies.

## 📁 Project Structure

```text
Ecommerce-Sales-Analysis/
│
├── ecommerce_sales_analysis.ipynb
├── ecommerce_sales_analysis_dataset.csv
└── README.md



🚀 How to Run the Project
Clone or download this repository.
Open ecommerce_sales_analysis.ipynb in Jupyter Notebook or JupyterLab.
Make sure the CSV dataset is in the same directory as the notebook.
Run the notebook cells sequentially.

👩‍💻 Skills Demonstrated
Data Cleaning
Exploratory Data Analysis
Data Visualization
Statistical Analysis
Business Analysis
Data Validation
Python Programming
Pandas
Matplotlib
Seaborn

📌 Future Improvements
Build an interactive Tableau dashboard
Perform deeper customer segmentation
Add sales forecasting
Perform advanced statistical analysis
Create SQL-based analysis of the same dataset
