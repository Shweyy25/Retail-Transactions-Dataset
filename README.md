This repository contains a comprehensive dataset of retail transactions, capturing various aspects of sales, including product details, customer information, and sales metrics. The dataset consists of over one million rows and includes detailed information on each transaction.

Dataset Information
Shape: (1,067,371 rows, 8 columns)
Columns:
InvoiceNo: Invoice number. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'C', it indicates a cancellation.
StockCode: Product (item) code. A 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name.
Quantity: The quantities of each product (item) per transaction.
InvoiceDate: Invoice date and time. The day and time when a transaction was generated.
UnitPrice: Product price per unit in sterling (£).
CustomerID: Customer number. A 5-digit integral number uniquely assigned to each customer.
Country: The name of the country where a customer resides.

Data Analysis Performed
Data Cleanup: Cleaning and preprocessing the dataset to handle missing values, incorrect data types, and outliers.
Product Quantity Distribution Analysis: Analyzing the distribution of product quantities per transaction.
Sales and Revenue Analysis:
Monthly, weekly, and daywise sales analysis.
Calculation of total revenue generated.
Countrywise Quantity and Sales: Analyzing product quantities and sales for each country.
Product Status Analysis: Analyzing the status of products, including cancellations and completions.
Top 10 Countries with Maximum Product Cancellations: Identifying the countries with the highest number of product cancellations.
Top 10 Products by Highest Revenue & Sale: Identifying the top products generating the most revenue and sales.
Top 10 Products with Maximum Cancellations: Identifying the products with the highest number of cancellations.
Customer Analysis:
Monthly (MOM) number of unique customers.
Countrywise number of unique customers.
