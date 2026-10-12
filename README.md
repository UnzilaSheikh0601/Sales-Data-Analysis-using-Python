# Sales Data Analysis Project

## Project Overview

This project analyzes a large sales dataset (180,000+ rows) to uncover business insights. The goal is to understand sales performance across products, time, and locations using data analysis and visualization.

It answers questions such as which products sell the most, which months generate the most revenue, and which cities contribute the most to sales.

## Dataset

- Type: Sales transaction data
- Size: 180,000+ rows
- Key Columns: Order ID, Order Date, Product, Quantity Ordered, Price Each, Purchase Address

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook
- Git & GitHub

## Project Workflow

- Data loading and understanding
- Data cleaning (missing values, duplicates, data types)
- Feature engineering (Total Price, Month, Hour, Weekday, City)
- Exploratory data analysis answering 10 business questions
- Data visualization
- Sales forecasting with linear regression

## Key Findings

- Best month for sales: December, with about $4.61M in revenue
- Top revenue city: San Francisco, at about $8.26M
- Best hour to run ads: 7 PM, based on total sales by hour
- Top product by revenue: Wired Headphones; top by quantity: AAA Batteries (4-pack)
- Most common product pair: Lightning Charging Cable & iPhone, bought together in 1,005 orders
- Average order value was nearly flat across cities, from about $191 (Los Angeles) to $196 (Atlanta), so city has little effect on how much customers spend
- Linear regression forecast: sales predicted at $3.72M, $3.85M, and $3.98M for the next 3 months

## Recommendations

- Schedule ads around 7 PM, the hour with the highest sales
- Bundle or cross-promote the Lightning Charging Cable with the iPhone, the most common product pair

## Limitations

- The data covers a single year, so there is no year-over-year comparison
- The forecast is a simple linear trend on monthly totals and does not capture seasonality, which is why it predicts below the December peak

## Visualizations Included

- Monthly sales bar chart
- Sales by city bar chart
- Sales by hour line chart
- Top products by quantity and revenue
- Price vs quantity scatter plot
- Average order value by city
- Sales by weekday
- Top 10 product pairs

## Conclusion

This project demonstrates practical data analysis skills, including data cleaning, exploratory analysis, visualization, and forecasting. It reflects real-world data handling and decision-making using Python.