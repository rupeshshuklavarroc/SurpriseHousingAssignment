# Surprise Housing 
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price

> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


### Objective
 - Which variables are significant in predicting the price of a house, and
 - How well those variables describe the price of a house.
 - The optimal value of lambda for ridge and lasso regression.
 
### Business Goal 
- Model the price of houses with the available independent variables. 
- This model will then be used by the management to understand how exactly the prices vary with the variables.
- The model will be a good way for management to understand the pricing dynamics of a new market.

## Table of Contents
* Problem Statement
* Objectives
* Business Goals
* Data Understanding and Exploration
* Model Building and Evaluation
* Model Comparison
* Summary
* Subjective Answers


## Summary
- For Lasso
    - Optimum Alpha = 0.01
    - R-Square (Train) = 0.93
    - R-Square (Test) = 0.92
- For Ridge
    - Optimum Alpha = 10.0
    - R-Square (Train) = 0.93
    - R-Square (Test) = 0.92

#### Top 10 Significant Features for Ridge
* OverallQual_9
* GrLivArea
* OverallQual_8
* Exterior1st_BrkFace
* Functional_Typ
* OverallCond_9
* Neighborhood_Crawfor
* SaleCondition_Alloca
* TotalBsmtSF
* Neighborhood_StoneBr

#### Top 10 Significant Features for Lasso
* OverallQual_9
* OverallQual_8
* SaleCondition_Alloca
* GrLivArea
* Exterior1st_BrkFace
* OverallCond_9
* Neighborhood_Crawfor
* Functional_Typ
* KitchenAbvGr_1
* GarageQual_Gd


## Libraries Used
- Numpy
- Pandas
- Matplotlib.pyplot
- seaborn
- sklearn linear_model, metrics
- sklearn model_selection train_test_split
- lasso, Ridge from sklearn.linear_model

## Technology Used
- Jupyter Notebook
- Python 3


