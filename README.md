# Home Sales Data Analysis

This project contains the code and files for analyzing home sales data using SparkSQL. The following steps outline the process followed to complete the project:

Setting up the Project

Created a new repository named "Home_Sales" specifically for this project.
Cloned the repository to the local computer for development.
Pushed the initial changes to the GitHub repository.
Data and Environment

Downloaded the provided "Module 22 Challenge files" and saved them locally.
Set up the development environment with PySpark and necessary dependencies.
Data Import

Renamed the provided Home_Sales_starter_code.ipynb file to Home_Sales.ipynb.
Imported the required PySpark SQL functions to work with SparkSQL.
Read the data from the home_sales_revised.csv file into a Spark DataFrame.
Performing SparkSQL Queries

Created a temporary table named home_sales from the DataFrame.
Executed SparkSQL queries to answer the following questions:
Average price for a four-bedroom house sold for each year (rounded to two decimal places).
Average price of a home for each year it was built with three bedrooms and three bathrooms (rounded to two decimal places).
Average price of a home for each year with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet (rounded to two decimal places).
"View" rating for homes costing more than or equal to $350,000, along with the query runtime (rounded to two decimal places).
Caching and Uncaching

Cached the temporary table home_sales to improve performance for subsequent queries.
Verified if the temporary table was successfully cached.
Ran a query using the cached data to filter out view ratings with an average price of greater than or equal to $350,000.
Compared the runtime of the cached query with the uncached runtime.
Partitioning and Querying Parquet Data

Partitioned the formatted Parquet home sales data by the "date_built" field.
Created a temporary table for the Parquet data.
Executed a query on the Parquet data to filter out view ratings with an average price of greater than or equal to $350,000.
Compared the runtime of the query on the Parquet data with the uncached runtime.
Final Steps

Uncached the temporary table home_sales.
Verified that the temporary table was successfully uncached using PySpark.
Downloaded the Home_Sales.ipynb file and uploaded it to the "Home_Sales" GitHub repository.
Please refer to the specific files and code in this repository for detailed implementation and further exploration of the home sales data analysis.