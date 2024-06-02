##Overview 

This project is focused on analyzing homes sales data using PySpark. This project accomplished the following tasks:

- The average price for a four-bedroom house sold for each year.
- The average price of a home for each year it was built, with three bedrooms and three bathrooms.
- The average price of a home for each year it was built, with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet, is determined. 
- The average price of a home per "view" rating, having an average home price greater than or equal to $350,000, is calculated. 
- The last query (average price of a home per "view" rating with an average home price greater than or equal to $350,000) is run using the cached data. The runtime is determined and compared to the uncached runtime
- The home sales data is partitioned by the "date_built" field and saved in parquet format
- A temporary table for the parquet data is created
- The last query is run again on the parquet data to calculate the average price of a home per "view" rating with an average home price greater than or equal to $350,000. The runtime is determined and compared
   to the uncached runtime.The home_sales temporary table is uncached and verified for uncaching using PySpark.
- Finally, the <a href="https://github.com/ElleNaazB/HomeSales/blob/main/Home_Sales.ipynb.ipynb"> Home_Sales.ipynb </a> file is downloaded from google colab and uploaded into this itHub repository.
