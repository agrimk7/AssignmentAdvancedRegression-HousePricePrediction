# Boombikes-LinearRegression-Assignment 
> Linear Regression performed on the Boombikes bike rental dataset as part of an assignment for coursework in the course Executive PG in Machine Learning and AI from IIIT Bangalore. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- 1. The optimal value of alpha is:
    - Ridge Regression- 2
    - lasso Regression- 50

- 2. r2 Scores:
    - Ridge  regression:  Train r2: 0.89 Test r2: 0.868
    - Lasso  regression:  Train r2: 0.891 Test r2: 0.87

- 3. After doubling the alpha for Ridge and lasso regression r2 score of training data has decreased slightly for both ridge and lasso regression

- 4. Top Features for House prediction are:

    - LotArea (Lot size in square feet)
    - OverallQual (Rates the overall material and finish of the house)
    - OverallCond (Rates the overall condition of the house)
    - YearBuilt (Original construction date)
    - Basement floor-related variables
    - GrLivArea (Above grade (ground) living area square feet)
    - TotRmsAbvGrd (Total rooms above grade (does not include bathrooms))
    - GarageCars (Size of garage in car capacity)




<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- sci-kit learn
- numpy
- seaborn
- matplotlib
- statsmodels


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@agrimk7] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->