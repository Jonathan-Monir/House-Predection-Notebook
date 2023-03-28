# House-Predection-Notebook

## Context
The real estate markets, like those in Sydney and Melbourne, present an interesting opportunity for data analysts to analyze and predict where property prices are moving towards. Prediction of property prices is becoming increasingly important and beneficial. Property prices are a good indicator of both the overall market condition and the economic health of a country. Considering the data provided, we are wrangling a large set of property sales records stored in an unknown format and with unknown data quality issues

## Introduction
In this project, we will be using polynomial regression for predicting the price of the house based on the features, then using KMeans clustering algorithm to group data into different categories based on their features. We will use data that contains information about different products and their prices. We will group products into 3 different categories and visualize each column with respect to the price column. Finally, we will draw some conclusions based on our results.

Data Description
We have a dataset with 10 different columns as follows:

date
Price
bedrooms
bathrooms
sqft_living
sqft_lot
floors
waterfront
view
condition


## Results
After running the KMeans algorithm, we obtained the following 3 categories:

Category 0: Products with prices ranging from 100000  to 400000 
Category 1: Products with prices ranging from 400000  to 600000 
Category 2: Products with prices ranging from 600000  to 1000000 

* 3 bedrooms are the most common number of bedrooms in all clusters.
* The area of living it's mean is in the highest in the medium category and not in the highest which is impressive.
* The most number of floors in all classes are 1 floor
* Most common grade in medium, highest categories are gade 7
* Many houses doesn't contain basement
## Conclusion

1. Time column had to be changed to datetime data type
2. Bedrooms had some unlogical values such as 33 bedrooms in one house
3. bathrooms was float that had decimal values such as 2.5, 3.75 that had to be treated with
4. many other values had outliers
5. After dealing with data, data fitted in the polonomial model to predict the price column
6. 3 categories was the best number suitable to cluster our data
7. after visualizing the clustered data we found many insights
