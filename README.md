# BigBasket_Prediction_MarketingAnalytics
This project is a hackathon conducted by Analytics Vidhya, is a market business problem where sales of each store must be predicted.

**My model is at the top 100 of the LeaderBoard**

## Overview
1. Deal with the null value with the help of imputer method in Python
2. Analyze the data to derive different insights and help to choose the algorithm
3. Compare different algorithm and selected Extra Trees Regressor based on negative mean absolute error with score of -753.9840726814722

## Problem Statement
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.

Using this model, BigMart will try to understand the properties of products and outlets which play a key role in increasing sales.

## Data Dictionary

We have train (8523) and test (5681) data set, train data set has both input and output variable(s)

1. Variable: 	Description
2. Item_Identifier: 	Unique product ID
3. Item_Weight:	Weight of product
4. Item_Fat_Content: 	Whether the product is low fat or not
5. Item_Visibility: 	The % of total display area of all products in a store allocated to the particular product
6. Item_Type: 	The category to which the product belongs
7. Item_MRP: 	Maximum Retail Price (list price) of the product
8. Outlet_Identifier: 	Unique store ID
9. Outlet_Establishment_Year: 	The year in which store was established
10. Outlet_Size: 	The size of the store in terms of ground area covered
11. Outlet_Location_Type: 	The type of city in which the store is located
12. Outlet_Type: 	Whether the outlet is just a grocery store or some sort of supermarket
13. Item_Outlet_Sales: 	Sales of the product in the particular store. This is the outcome variable to be predicted

## Insights
1. Item visibility and item sales outlet is left skewed is left skewed, we can use standard scalar for normalization
2. as we can see in the plot they are not seperated by linear regression we can try decision tree, random forest or boosting technique to split the and predict data(using information gain or gini index) or SVR
3. We can see that low sales has comparatively low visibility
4. High MRP has comparatively low sales
5. Mean are almost the same for low fat and regular but regular has little more sales than lowfat
6. soft drinks, baking goods, and health and hygene has comparatively low sales
7. Grocery store has a really low sales
8. Teir has comparatively low sales
9. 1998 we can see has low sales
10. small size has comparatively low sales


## Video of the Analysis and prediction
[<img src="https://img.youtube.com/vi/rvDZ_jIoIho/maxresdefault.jpg" width="60%">](https://youtu.be/rvDZ_jIoIho)
