# amazon_reviews_spark
Amazon customer review analysis using Apache Spark
In this project, we have taken [Amazon customer reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) and the dataset has been taken from the amazon’s official website by web scraping. We have used multilingual reviews dataset which contains the reviews of US marketplace only. The data contains The data consist of 7 million reviews and ratings given by the customers over 20 years from year 1995 to 2015. 


Analyzing these reviews and ratings provide useful insights about customers behaviour. We analyzed customer reviews to find answers of business problems such as are user inclined more towards higher rating products, does the length of the review and words used in review headline influences user decision, does low rating and bad reviews restricts customer to purchase the product etc. 
## Tools and technologies used
* Big data technologies: Azure Databricks, Configuration 6.0 Conda Beta with 2 nodes, Apache spark 2.4.3, Scala 2.11
* Programming Language : Python, pyspark.sql
* Other Libraries and packages used : requests, pandas, matplotlib.pyplot, seaborn
## Data Analysis and Statistics
* Total number of unique products: 52380
* Total product categories: 38
* Total number of customers : 4112395
* Maximum star ratings :  64% customers give 5 star ratings
* Product category which got highest Average rating : Automotive with avergae rating 4.59/5
* Product category with Maximum reviews category : Mobile Apps with a cout of over 1 million reviews
