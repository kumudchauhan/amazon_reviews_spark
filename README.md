# Amazon Customer Reviews analysis using Apache Spark

In this project, I extracted [Amazon customer reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) and the dataset has been taken from the amazon’s official website by web scraping. I have used multilingual reviews dataset which contains the reviews of US marketplace only. The data consist of 7 million reviews and ratings given by the customers over 20 years from year 1995 to 2015. 

## Business Problem
Analyzing these reviews and ratings provide useful insights about customers behaviour. I am mainly interested in analyzing customer reviews to find answers of business problems such as are users inclined more towards high rating products, does the length of the review and words used in review headline influences user's decision, does low rating and bad reviews restricts customer to purchase the product etc. Finding top words used by the customers in the reviews to understand their sentiments and some more details complemented to the product ratings. 

This type of analysis can provide helpful information to any e-commerce or other businesses who are getting feedback/reviews from their customers. These techniques can be helpful for customer success, customer retention by providing a better understanding of their customers behaviour and product qulaity.

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
* Product category with Maximum reviews category : Mobile Apps with a count of over 1 million reviews

### Note: For more detailed analysis and visualization please refer pdf file.
