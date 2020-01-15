# Cincinnati-Housing-Price-Prediction

### Project link : http://rpubs.com/shreyjparth/562705

### The goal of this project is to predict the house prices in city of Cincinnati by observing the potential predictive power of a number of variables on the house prices. 

My assumption prior to starting this project is that the sold prices of houses should be correlated to and perhaps predicted by various external indicators. For example, the notion was that if a house has more bedrooms/bathrooms, then the house sale price would be higher than that of the houses with less number of bedrooms/bathrooms.

Currently our data has 380 observations, but as this is a proposal report, we plan to add more observations to enhance our model. Through several iterations of this analysis we are hoping to eliminate unnecessary and irrelevant regressor variables and end up with a simplified regression equation to get the best possible prediction.

#### We began with the following 16 covariates with 1 response variable: 
1. Sold Price: Our response variable. 
2. Zip Code(categorical)
3. Sold Date
4. Number of bedrooms 
5. Number of full bathrooms 
6. Number of half bathrooms 
7. Stories 8. Year Built 
9. Sqft 
10. Lot Size 
11. Total number of rooms 
12. School Distance 
13. Parking Capacity 
14. Parking Size 
15. Basement Size 
16. Lawn (categorical)
17. Patio (categorical)
18. Average price per square feet

### Techniques involved:
1. **Exploratory data analysis
2. **Linear Regression
3. Ridge and Lasso Regression
4. Forward and backward feature selection
5. Box-cox Transformation
6. K-fold cross-validation

### Final model showed the most important variables as:
1)Number of full bathrooms
2)Number of bedrooms
3)Parking Capacity
4)Zip Code
5)Total number of rooms
6)Average price per square feet
7)Number of half bathrooms 

