# Home_Sales
In this assignment, I have used my knowledge of SparkSQL to determine key metrics about home sales data. I have used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached. 

## Following steps are followed to complete the requirements of the challenge:
Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

Import the necessary PySpark SQL functions for this assignment.

Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

Create a temporary table called home_sales.

## Answer the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

## RESULTS
The query run time for uncached data is 0.755555 seconds.

The query run time for cached data is 0.46856 seconds.

The query run time for parquet data is 0.38534 seconds.