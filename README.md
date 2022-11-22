# Bike-Sharing-Demand-Prediction
Performed an analysis using Supervised Regression Models to predict the count of Bike Sharing Demand

# Project Title : Bike_Sharing_Demand_Prediction_Capstone_Project

# Problem Description:
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Steps Involved
* Exploratory Data Analysis
![image](https://user-images.githubusercontent.com/46549606/186166437-7f4038a2-8b4a-4a23-8cdd-196a65a96516.png)

* Extracting features from date
* Model Building
1. Linear Regression
2. Lasso Regression
3. Ridge Regression
4. ElasticNet Regression
5. DecisionTree Regressor
6. RandomForest Regressor
7. Gradient Boost
8. Xg Boost
* Model Evaluation through Metrics :
1. Mena Squared Error
2. Root Mean Squared Error
3. R-Squared
4. Adjusted R-Squared
 
# Model Summary
![image](https://user-images.githubusercontent.com/46549606/169807851-2e81d6f0-798b-469b-a3f2-4118b31ddd74.png)



# Conclusions:

* As it was stated in the problem, rented bike count was low in 2017 untill november. After that rented bike count started increasing.
* There was sharp increase in demand from the end of 2017 that too in winter season of the year. The demand however decrease at the end of 2018.
* Bike count rent is highly correlated with 'Hour', which seems obvious. Demand for bike is mostly in morning (7 to 8) and in the evening (3 to 9).
* After doing exploratory data analysis, applying Linear Regression model didn't go quite well as it gave only 67.109325% accuracy.
* Lasso and Ridge Regression helps to reduce model complexity and prevent over-fitting which may result from simple linear regression. with Lasso, ridge and       ElasticNet regressor We got r squared value of 0.67106525, 0.67109331, 0.67109188 respectively.
* With Decision Tree we are able to achieve the r2 score of 0.811.
* Random forest regressor gave r squared value of 0.911 on test data.
* Gradient Boost gives higher value of R squared metric in train data 0.947 and on test data it is 0.912
* XG Boost gave r squared value of 0.9164
* XG Boost came with best accuracy to approximate numbers of rented bikes demand. It gives amazing results of training r-square at 0.97 and test r-square value at 0.9164 also with adjusted r-square with 0.911.

# Next Step :
Implementing the model on production will give us a prediction of exact number of bikes to be placed so as to met demand, for peek hours there can be over prediction which will eventually not a problem but during the least demand hours the underprediction could be an issue , solving this would make the model ready for production.

