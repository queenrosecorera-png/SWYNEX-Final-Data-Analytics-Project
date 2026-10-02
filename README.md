# SWYNEX-Final-Data-Analytics-Project

# Online Retail Sales Analysis

## About the Project

This is my final data analytics project based on the Online Retail II dataset.

The main goal of this project was to take raw retail transaction data, clean it, analyze it, and create a dashboard to understand sales and customer behaviour.

I worked on the project in three stages:

1. Data Cleaning
2. Data Analysis
3. Dashboard Creation

I used Python for cleaning and analysis and Power BI for creating the dashboard.

## Problem Statement

The raw retail data contained more than one million transaction records and had issues such as missing values, cancelled invoices, duplicate records, and inconsistent data.

I wanted to understand the sales data better and find useful information such as:

- How much revenue was generated?
- Which products generated the most revenue?
- Which customers contributed the most revenue?
- Which countries had the highest sales?
- How did revenue change over time?
- How many transactions were cancelled?

## Dataset

I used the Online Retail II dataset for this project.

The dataset contains online retail transactions from December 2009 to December 2011.

Some of the main columns are:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

The original dataset contains more than 1 million records.

## Data Cleaning

I first explored the dataset to understand its structure and identify data quality issues.

The main cleaning steps I performed were:

- Checked the number of rows and columns.
- Checked missing values.
- Checked duplicate records.
- Identified cancelled invoices.
- Checked quantity and price values.
- Converted the date column into the correct format.
- Created a revenue column using Quantity × Unit Price.
- Saved the cleaned data for further analysis.

## Data Analysis

After cleaning the data, I analyzed it using Python and Pandas.

I looked at:

- Total revenue
- Revenue trends over time
- Revenue by country
- Top products by revenue
- Top customers by revenue
- Cancelled transactions
- Customer contribution to revenue

I also looked at the top 10% of customers to understand how much of the total revenue they contributed.

## Dashboard

I created a Power BI dashboard to present the main results in an easier way.

The dashboard includes:

- Total Revenue
- Total Transactions
- Cancellation Rate
- Revenue Trend
- Revenue by Country
- Top Products
- Top Customers

The dashboard also allows users to interact with the data using filters.

## Key Insights

From my analysis, I found that:

- The United Kingdom contributed a large share of the total revenue.
- A smaller group of customers contributed a significant amount of revenue.
- Some products generated much more revenue than others.
- Revenue changed across different periods.
- Cancelled transactions had an impact on the overall sales results.

These findings helped me understand the sales and customer patterns in the dataset.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Power BI
- GitHub
