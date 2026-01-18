# Project Name
This project's goal is to build a robust regression model that will predict house prices in Australian market
The model is deisgned to identify low values properties that are of importance for the company to flip 
To achieve this goal, we are using Ridge and Lasso Regression 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- The project is for a US Housing Company that wants to predict house prices in australia using data analytics. To enter the complete new australian market,
company needs some pointers on low or undervalued properties with the help of regression models. We are using two regressions - Ridge and Lasso to predict the real value of house properties and provide a proper statistics for the company to take decision if investment in them is good or bad 


- Business Problem. 

The company wants to know which variables are significant and which of them to ignore to predict the house price

- Dataset Information. 

The train.csv has various numerical and categorical variables


## Conclusions
- Conclusion 1. 
The dataset train.csv has a huge multicollinearity therefore making regularization an important step in the code
we can see strong correlations between multiple predictor variables thereby making the choice to use Ridge & Lasso regression perfect for this business problem

- Conclusion 2. 
Housing prices are driven by the factors like size, quality, basement size, how big a garage is.

- Conclusion 3. 
Ridge Regression is the best choice as the final model based on its superior performance and seeing how stable it is when there is multicollinearity present    



## Technologies Used
- python - version 3.9.6
- seaborn - version 0.13.2
- matplotlib - version 3.9.4
- pandas - version 2.3.1

