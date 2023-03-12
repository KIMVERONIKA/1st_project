# 1st_team_project Data-HousePrice Predicting House Prices Regression

## Objective/Goal
To identify the variables affecting house prices, e.g. area, number of rooms, bathrooms, etc.

To create a linear model that quantitatively relates house prices with variables such as number of rooms, area, number of bathrooms, etc.

To know the accuracy of the model, i.e. how well these variables can predict house prices.

## Role
We worked independently for 1,5month for our 1st_team project to extract, clean, analyze, visualize, create pipeline and fit house price data.

## Data
Use housing dataset. It contains 1460 training data points and 81 features that might help us predict the selling price of a house.

## Tools Used

Mean Median Imputer
Categorical Imputer
RareLabel Encoder
EqualWidth Discretiser
One Hot Encoder
Sklearn TransformerWrapper
Drop Constant Features
Smart Correlated Selection
Standard Scaler


## Models Used

KNeighbors Regression,

Linear Regression,

Lasso, 

XGB Regression,

Support Vector Regression

## Code 

Code for this project can be found here: https://github.com/KIMVERONIKA/House_Price/blob/main/Final%20house%20price.ipynb

## Results
We did data analysis, found empty values, replaced them, replaced the numerical and categorical values, encoded, found correlating variables, created a pipeline, and trained regression models. The best SVR model the results is train set score 97% and test 86%.
