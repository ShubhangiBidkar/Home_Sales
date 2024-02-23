# Home_Sales


1.Answer the following questions about home sales using SparkSQL:

  * What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
  * What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
  * What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
  * What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

2.Cache your temporary table home_sales.

3.Check if your temporary table is cached.

4.Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

5.Partition by the "date_built" field on the formatted parquet home sales data.

6.Create a temporary table for the parquet data.

7.Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

8.Uncache the home_sales temporary table.

9.Verify that the home_sales temporary table is uncached using PySpark.

## File Notes

 Home_Sales_colab.ipynb conatins the solution for the challenge instructions.
