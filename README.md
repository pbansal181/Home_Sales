# Home_Sales

** Instructions** 

1. Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

2. Import the necessary PySpark SQL functions for this assignment.

3. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

4. Create a temporary table called home_sales.

5. Answer the following questions using SparkSQL:

	- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

	![image](https://github.com/pbansal181/Home_Sales/assets/148804724/12938f71-684d-47b4-8ad8-ae204a203c83)

	- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

 	![image](https://github.com/pbansal181/Home_Sales/assets/148804724/676b8d5d-cab4-4ff6-954d-4b52304b88df)

	- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? 	Round off your answer to two decimal places.

	![image](https://github.com/pbansal181/Home_Sales/assets/148804724/babdc60d-a785-4862-a20a-ed6d7185b6ae)

	- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your 	answer to two decimal places.

	![image](https://github.com/pbansal181/Home_Sales/assets/148804724/dfa31d93-83e4-48bd-b099-a9f70190abc6)

6. Cache your temporary table home_sales.

7. Check if your temporary table is cached.

8. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

9. Partition by the "date_built" field on the formatted parquet home sales data.

10. Create a temporary table for the parquet data.

    ![image](https://github.com/pbansal181/Home_Sales/assets/148804724/791121f3-bc56-4e17-a3f7-28f7779c2fc6)

11. Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

12. Uncache the home_sales temporary table.

13. Verify that the home_sales temporary table is uncached using PySpark.
    
    ![image](https://github.com/pbansal181/Home_Sales/assets/148804724/dd98b79d-4214-4fef-b7e3-f988b2a08dd7)


14. Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.

