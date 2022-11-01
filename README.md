# House sale price prediction model
>  To build a regression model with regularisation to model the price of houses with the available independent variables. Find which variables are significant in 
   predicting the price of a house, and how well those variables describe the price of a house. Also get optimum lambda values for ridge and lasso regularisation
    model.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information 
- The business problem 
  To build a regression model with regularisation to model the price of houses with the available independent variables. This model will then be used by the
  management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas 
  that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- Dataset that is being used
  A data set from the sale of houses in Australia.

 The main objective is find variables that are significant in predicting bike share demand and quantify how significant they are in prediction.
  A Linear Regression model with regularisation is created for this objective. The coefficients of the model tell us how significant they are in predicting bike share demand.

Steps done
1) Data understanding and EDA
   - Missing value treatment
   - Drop unncesssary and redundnat column
   - Drop duplicate data
   - identify target variable
   - EDA and outlier treatment
   - create derieved columns

2) Data preparation
   - create dummy variables for categorical variables
   - split into traina and test sets
   - scaling

3) Model Building and Evaluation
   - Automated RFE
   - Linear regression
   - Ridge Regression
   - Lasso Regression'
   - Choosing best model

4) Validation of LR assumptions
5) Best predictors and interpret results

## Conclusions
1) Top three significant predictors of sale price are: GrLivArea, OverallQual, LotShape_IR3 with coefficinets 0.61,0.38,-0.23.
2) top 10 there are variables that are significant in predicting the share bike demand which are:
   GrLivArea, OverallQual, LotShape_IR3,GarageCars, LotArea, ExterQual_Gd, OverallCond, BsmtFullBath,Neighborhood_NridgHt and LotFrontage.

3) 8 variables are positively related with bike demand : GrLivArea,OverallQual,GarageCars, LotArea, ExterQual_Gd, OverallCond, BsmtFullBath and Neighborhood_NridgHt	
   2 variables are negatively related with bike demand : LotShape_IR3 and LotFrontage
4) Optimum lambda values
   - Ridge regression = 0.1
   - Lasso regression = 0.0001


## Technologies Used
- Notebook - version 6.4.8
- pandas - It is used for data cleaning and analysis. 
- numpy - NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, and matrices like to get mean,median etc. 
- seaborn  - Seaborn is a library for making statistical graphics in Python.
- matplotlib.pyplot  - Matplotlib is a cross-platform, data visualization and graphical plotting library for Python.
- scikit-learn - machine learning library for the Python programming language. It features various classification, regression and clustering algorithms including support-vector machine.

## Acknowledgements
- This project was inspired by Upgrade.
- References: google, stackoverflow, upgrad classes.


## Contact
Created by [https://github.com/gokul-gopan-k] - feel free to contact me!


