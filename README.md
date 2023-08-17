![image](https://github.com/mcaro01/Home_Sales/assets/125619215/8babf4fc-4c51-47a2-a9ba-39fc8dea7677)


# Home_Sales

### Instructions:
  1. Rename the `Home_Sales_starter_code.ipynb` file as `Home_Sales.ipynb`.

  1. Import the necessary PySpark SQL functions for this assignment.

  1. Read the `home_sales_revised.csv` data in the starter code into a Spark DataFrame.

  1. Create a temporary table called `home_sales`.

  1. Answer the following questions using SparkSQL:

     - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    
     - ![image](https://github.com/mcaro01/Home_Sales/assets/125619215/95cf4c17-cfa0-4b49-9bc5-279e8504bc37)

    
     - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal         places.
    
     - ![image](https://github.com/mcaro01/Home_Sales/assets/125619215/ea97a300-5cf8-437a-b642-5c0394b71309)


     - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000             square feet? Round off your answer to two decimal places.
    
     - ![image](https://github.com/mcaro01/Home_Sales/assets/125619215/60f73582-adf5-4765-a26b-74f066e2e5e8)


     - What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
    
     - ![image](https://github.com/mcaro01/Home_Sales/assets/125619215/eff687c4-44a8-459f-8ab3-61d00590e57c)


  1. Cache your temporary table `home_sales`.

  1. Check if your temporary table is cached.

  1. Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

     ![image](https://github.com/mcaro01/Home_Sales/assets/125619215/4914abb3-7ce6-4f97-a213-47e8f34a5630)


  1. Partition by the "date_built" field on the formatted parquet home sales data.

  1. Create a temporary table for the parquet data.

  1. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
  ![image](https://github.com/mcaro01/Home_Sales/assets/125619215/cac9688f-e328-4e9b-aab8-50a0e79af129)

  1. Uncache the `home_sales` temporary table.

  1. Verify that the `home_sales` temporary table is uncached using PySpark.

  1. Download your `Home_Sales.ipynb` file and upload it into your "Home_Sales" GitHub repository.
