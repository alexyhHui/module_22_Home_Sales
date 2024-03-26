# Home_Sales

In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Instructions

Answer the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

![image](https://github.com/alexyhHui/module_22_Home_Sales/assets/147750285/f2106ce7-e814-48c1-b55f-8ccc49f48fe0)

What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

![image](https://github.com/alexyhHui/module_22_Home_Sales/assets/147750285/9ffc747a-2a68-4682-8196-6cb815af67ac)

What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

![image](https://github.com/alexyhHui/module_22_Home_Sales/assets/147750285/22f456b1-46f8-4278-b046-af97daec91ca)

What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

![image](https://github.com/alexyhHui/module_22_Home_Sales/assets/147750285/5fa09a8e-38ba-4770-abde-e56cc85d8c3c)

Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

![image](https://github.com/alexyhHui/module_22_Home_Sales/assets/147750285/e7a36693-b4d0-483e-99df-19bf3b4d2427)

Using the parquet data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

![image](https://github.com/alexyhHui/module_22_Home_Sales/assets/147750285/64df0635-3e45-443c-8f3f-ce3c1802ac9c)


The fastest runtime is using the cached data.
