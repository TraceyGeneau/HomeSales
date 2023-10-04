# Home Sales


The data files, home_sales_revised.csv was obtained from the following URL:

https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv

Using Colab, the following questions were answered regading the CSV file:

** 1.  What is the average price for a four-bedroom house sold for each year? **

The average price for four bedroom homes each year was as follows:

INSERT PHOTO 1

2.  What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?

The average price for a three bedroom, 3 bathroom home per year was as follows:

INSERT PHOTO 2

3.  What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?

The average price of a 3 bedroom, 3 bathroom home with two floors and that is greater than or equal to 2000 feet was as follows:

INSERT PHOTO 3

4.  What is the "view" rating for homes costing more than or equal to $350,000?

The average view rating for homes that are greater than or equal to $350,000 was 32.26.

This data had a runtime of 0.39 seconds.  

Insert Photo 4 


When we cached the data and reran the "view" rating query, the run time was 0.15 seconds.  The cached query was running 39% of the time it took to run the uncached query. 

INSERT PHOTO 5

Here is the count of the Parquet Data count that was grouped by date_built was as follows:

Insert photo 7



When the Home sales view was partitioned it took the same time as the uncached query with 0.36 seconds.

Insert PHOTO 6








