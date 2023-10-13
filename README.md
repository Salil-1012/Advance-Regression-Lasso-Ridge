# Advance Regression Surpirise Housing 
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

> The company wants to know:

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
-  The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.


- What is the business probem that your project is trying to solve?
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The Ridge and Lasso regression r-2 score of train and test set .
- Ridge : Train :90.6% Test :86.9%
- Lasso : Train :91.8% Test :87.0%

> The most significant variables which help in increase in Sales in Ridge are -:
('SaleCondition_Partial', 0.135)
('SaleCondition_Normal', 0.094)
 ('GarageFinish_Family', 0.09)
('SaleCondition_Alloca', 0.087)
 (GarageFinish_Unknown', 0.084)
 ('SaleCondition_AdjLand', 0.084)

> The most significant variables which help in increase in Sales in Lasso are -:
('SaleCondition_Partial', 0.31)
 ('SaleCondition_Normal', 0.254)
('GarageFinish_Family', 0.248)
 ('SaleCondition_Alloca', 0.221)
 ('SaleCondition_AdjLand', 0.221)
(GarageFinish_Unknown', 0.171)

- So in the concept of regulariztion we need model that can find the genereal pattern in data and they should work well in unseen    data so we use penality in the regression model -: 
- I used the best score for aplha in Ridge Regression - : 10
- Moreover, the best score for the lasso Regression -: 0.00006

- So In this Model I used to prefer the Lasso Regression 


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
## Technologies Used
- sklearn - version 1.0.2
- pandas - version 2.0
- numpy - version 1.22.3
- matplotlib -version 3.5.1
- statsmodels -version 0.14.0


## Contact (GitHub)
Created by: 
- [GitHub -: Salil Chandan](https://github.com/Salil-1012) 

## Connect with me on LinkedIn:-
- [Linkdin -: Salil Chandan](https://www.linkedin.com/in/salil-chandan)



