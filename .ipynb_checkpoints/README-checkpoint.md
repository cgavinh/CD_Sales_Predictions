# Linear Regression for Sales Predictions
## Linear regression was found to be the best model for making sales predictions

** Coire Gavin-Hanner **

### Business Problem
Stores often collect data about the items they put out on their floors and sales numbers, but it is not obvious how all of the data are connected. Here we try to build a machine learning algorithm that can predict sales numbers from other store data.

### Data

The data set came from the Coding Dojo and contains data on different items sold at grocery stores.

## Insights

There is a moderate correlation between the age of a store and the wieght of items sold there. 

<img src='heatmap.png'>


By looking at the boxplots below, we can see that Dairy sells better in larger stores, but Seafood sells better in smaller stores. 

<img src='sales_v_dairy.png'>
<img src='sales_v_seafood.png'>

## Model Summary

I used a linear regression model to predict item sales. It had an r-squared value of 0.566
and an RMSE value of 1094.338. This indicates that it was not a good predictive model, but it was better than the others I used. 

## Final Recommendations

I would recomment finding a different ML model to predict item sales. Based on my statistical analyses, I would recommend smaller stores sell more seafood and larger stores sell more dairy. 