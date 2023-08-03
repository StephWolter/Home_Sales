# Home_Sales
# Measure time for calculation between cached data and compare with using parquet.

## SetUp

* Create Repository in GitHub.
[Home_Sales](https://github.com/StephWolter/Home_Sales.git)

* Clone repository to personal computer, then create the folder structure:

            * Home_Sales_colab.ipynb         # data pulled by script is held in AWS S3 buckets
            * README.md



## Data Analysis
* Imported necessary libraries, initialized data.
* Created home_sales_df
* Created a temporary view
* Using Spark.Sql answered following questions:
    * What is the average price for a four-bedroom house sold for each year?
    * What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?
    * What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? 
    * What is the "view" rating for homes costing more than or equal to $350,000?
        * I had some difficulty with this understanding what the "view rating" is.  Tried to use a RANK function.

## Wrote out README
* Ta-da!
