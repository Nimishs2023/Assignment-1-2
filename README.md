# Project Name
Assignment - Housing Data Analysis


## General Information
Surprise Housing, a US-based housing company, is entering the Australian market. The company uses data analytics to purchase houses at a price below their actual value and then sell them at a higher price. To this end, the company has collected a dataset of house sales in Australia. The company is now looking at prospective properties to buy and wants to build a regression model using regularization to predict the actual value of the properties and decide whether to invest in them.

The company wants to know which variables are significant in predicting the price of a house and how well those variables describe the price of a house. The company also wants to determine the optimal value of lambda for ridge and lasso regression.

The business goal is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. The management can then manipulate the strategy of the firm and concentrate on areas that will yield high returns. The model will also be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
The optimal value of lambda for ridge regression is 10 and for lasso regression is 1. These values were determined using GridSearchCV to find the best hyperparameters for the models.

The significant variables according to RFE are: ‘GarageFinish_Fin’, ‘GarageFinish_RFn’, ‘GarageFinish_Unf’, ‘GarageQual_Ex’, ‘GarageQual_Fa’, ‘GarageQual_Gd’, ‘GarageQual_Po’, ‘GarageQual_TA’ and ‘PavedDrive_Y’.
