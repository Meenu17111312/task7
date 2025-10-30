# Task 7 - Sales Data Analysis using SQLite in Python

## Objective

To perform SQL-based sales analysis on the Amazon Store dataset using
Python, SQLite, and Pandas.

## Steps Performed

1.  Loaded `sales_data_amazon.csv` into Python.
2.  Created SQLite database `sales_data.db`.
3.  Inserted data into table `sales`.
4.  Ran SQL query to calculate total quantity and total revenue for each
    product.
5.  Displayed results and visualized data using Matplotlib and Seaborn.

## SQL Query Used

``` sql
SELECT product_name,
       SUM(quantity) AS total_quantity,
       SUM(sales) AS total_revenue
FROM sales
GROUP BY product_name
ORDER BY total_revenue DESC;
```

## Results

-   Two bar charts show total quantity and total revenue per product.
-   The analysis highlights which products are top sellers and revenue
    generators.

## Tools Used

-   Python
-   SQLite3
-   Pandas
-   Matplotlib
-   Seaborn

## Files Included

-   Task7_Sales_SQLite.ipynb
-   Task7_Sales_Report.pdf
-   sales_data_amazon.csv


Your Name
