# House Price Prediction Assignment
Assignment on predicting the house price based on advanced regressions concepts


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
### Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.

### Business Goal 
 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


### Solution Approach

The solution is divided into the following sections: 
- Data understanding and exploration
- Data cleaning
- Data preparation
- Model building and evaluation
- Determine the optimal value of lambda for ridge and lasso regression

## Conclusions
Used Ridge and Lasso Regression and based on the analysis, the following conclusion is derived.
R2 score of approx 0.83 is achieved on both Ridge and Lasso Models. The following factors mostly influence the house price as demonstrated by both the models:-
- OverallQual	
- LotArea	
- TotRmsAbvGrd	
- LotFrontage	
- GarageYrBlt	
- GarageCars	
- OverallCond	
- Fireplaces	
- GarageArea	
- MasVnrArea	
- BedroomAbvGr	
- KitchenAbvGr	

## Technologies Used
- Python 3.11.4

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@satyap84] - feel free to contact me!


