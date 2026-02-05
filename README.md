# Sales Data Analysis using SQL and Python

## Project Overview

This project analyzes a retail sales dataset using SQL queries and Python to generate business insights. The goal of the project is to understand sales performance, identify top-performing categories, and visualize trends using charts.

This project demonstrates skills in data analysis, SQL querying, and data visualization, which are essential for data analyst and freelancing roles.

## Objectives

* Analyze total sales and revenue
* Find category-wise sales performance
* Identify top-selling products
* Visualize sales trends using charts

## Tools and Technologies

* Python
* Pandas
* Matplotlib
* SQLite / SQL
* Jupyter Notebook

## Project Workflow

1. Load the sales dataset into a database
2. Perform SQL queries to extract insights
3. Use Python (Pandas) to analyze data
4. Create visualizations using Matplotlib
5. Interpret results and summarize findings

## Example SQL Query

```sql
SELECT category, SUM(amount) AS total_sales
FROM sales
GROUP BY category;
```

## Output

The project generates:

* Category-wise sales report
* Summary statistics
* Bar charts showing sales distribution

## Skills Demonstrated

* Data Cleaning
* SQL Aggregations (SUM, GROUP BY)
* Data Visualization
* Business Insight Generation

## Folder Structure

```
sales-analysis-sql-python/
│
├── sql-python data analysis project.ipynb
├── dataset.csv (if included)
└── README.md
```

## Future Improvements

* Add dashboard using Power BI
* Add more visualizations
* Automate report generation

## Author

Harshitha K M
Aspiring Data Analyst | Python | SQL | Power BI

