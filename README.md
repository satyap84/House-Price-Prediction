# Advanced-Regression-HousePrice-Prediction
Advanced Regression by using Ridge and Lasso Regression to predict house sale price


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Problem Statement: 
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company wants to know, which variables are significant in predicting the price of a house, and how well those variables describe the price of a house.

- Business Goal:
Model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. The model will be a good way for management to understand the pricing dynamics of a new market.

- Dataset:
Company has provided train.csv file with the dataset.

- Approach:
We can determine the optimal value of Lambda for Ridge and Lasso regression to identify which predictor variables are most important that impacts the Sale Price of the prospective properties.

## Conclusions
Used Ridge and Lasso Regression and based on the analysis, the following conclusion is derived.
R2 score of approx 0.81 is achieved on both Ridge and Lasso Models. The following factors mostly influence the house price as demonstrated by both the models:-

- Total area in square foot
- Total Garage Area
- Total Rooms
- Overall Condition
- Lot Area
- Centrally Air Conditioned
- Total Porch Area (Open + Enclosed)
- Lot Frontage
- Neiborhood Stone Brook

## Technologies Used
- Python 3.11.4

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
