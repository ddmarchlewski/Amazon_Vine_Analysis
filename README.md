# Amazon_Vine_Analysis

## Overview
In this project, we are to pick and analyze a dataset from amazon reviews. We are analyzing the data by using PySpark to perform the ETL process by extracting the dataset, transform the data, and then connect it to the database that was provided for me by the AWS webserver. 

## Results
There were 40,565 total number of reviews. 

![total_number_of_reviews](https://user-images.githubusercontent.com/80054925/124402454-ef034800-dcf5-11eb-8391-77c537b28159.png)

15,711 of those reviews were 5 stars.

![five_star_reviews_total](https://user-images.githubusercontent.com/80054925/124402543-7c469c80-dcf6-11eb-86f3-182eaff1634e.png)

38.2% of the five_star reviews were vine and 38.9% of the five_star reviews were non-vine.

![percentages](https://user-images.githubusercontent.com/80054925/124402583-c2036500-dcf6-11eb-9260-d3498d940012.png)

## Summary
After performing this analysis, there does not seem to be any positivity bias. This is because the percentages are so close together. Both being around 38 percent. We could look at the mean, median, and mode of the star ratings for Vine and non-Vine reviews.  
