# Surprise Housing Advance Linear Regression Case Study
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Determine the optimal value of lambda for ridge and lasso regression


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information

- Background : A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below..

- Business Problem: You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market. 

- Approach: You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

- Dataset used: Data dictionary and train data is issued through the time period.


## Conclusions
-Choose lambda for lasso regression because with optimum value of lambda lasso regression’s R square value is higher than ridge and also since all the columns were taken into consideration (grid search cross validation is not performed) lasso regression makes many  non-important predictor variables coefficients zero and gives only important  predictor variables which impacts house price. 

Final Prediction:
Variables are significant in predicting the price of a house are :
• GrLivArea: Above grade (ground) living area square feet, • OverallQual: Rating as very excellent(10) and excellent(9) for the overall material and finish of the house as very excellent and excellent, • RoofMatl_WdShngl: Roof marterial as wood shingles, • FullBath_3: full bathroom as 3, • LotArea: Lot area in square feet, • Condition2_PosN: Proximity to various condition as PosN, • Fireplaces_3 : Number of fireplaces as 3, • KitchenQual_TA: Kitchen Quality as TA, • TotRmsAbvGrd_11: Total rooms above ground.

How well those variables describe the price of a house:
Predictor variables GrLivArea, OverallQual_10, RoofMatl_WdShngl impacts housing price positively while predictor variables Condition2_PosN, Fireplaces_3, KitchenQual_TA, TotRmsAbvGrd_11 impacts housing price negatively.

The optimal value of lambda for ridge and lasso regression is 20 and for lasso is 0.0001 respectively

Overall we have a decent model, but we also acknowledge that we could do better.

## Technologies Used
- library - pandas
- library - matplotlib
- library - seaborn


## Acknowledgements

- This project was inspired by live sessions and course material for Executive PG Programme in Machine Learning & AI - September 2023


## Contact
Created by @nishtha0807  - feel free to contact me!



Data Sourcing and importing required libraries for EDA


