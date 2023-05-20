# Big Data Challenge --Home Sales
![big-data-concept.jpg](images/big-data-concept.jpg)
## Overview
In this challenge, SparkSQL is used to determine key metrics about home sales data. Then, Spark is used to create temporary views, partition the data, cach, uncach the temporary table and run the different queries with various setting.

## Steps of Projects
* 1.Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

* 2.Import the necessary PySpark SQL functions for this assignment.

* 3.Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

* 4.Create a temporary table called home_sales.

* 5.Analyze the following questions using SparkSQL:

   * the average price for a four-bedroom house sold for each year

   * the average price of a home for each year it was built that has three bedrooms and three bathrooms

   * the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet

   * the "view" rating for homes costing more than or equal to $350,000

* 6.Cache your temporary table home_sales.

* 7.Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

* 8.Partition by the "date_built" field on the formatted parquet home sales data, and create a temporary table for the parquet data.

* 9.Run the queries,determine the runtime and compare it to uncached runtime.

* 10.Uncache the home_sales temporary table.


