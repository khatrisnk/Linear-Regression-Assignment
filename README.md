# Linear Regression Assignment

## Problem Statement

A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

## Objective

Company want to understand the factors affecting the demand for these shared bikes in the American market. They wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands.

## Business Goal

To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Data Sourcing

The company already given the data set containing the information about the bike sharing for year 2018 and 2019.
For this case study we need to focus only on provided dataset given by company.

## Platform Used

    - Kaggle

## Library Used

    - Pandas
    - Numpy
    - Matplotlib
    - Seaborn
    - sklearn
    - statsmodels


## Equation for Best fit line

We can see that the equation of our best fitted line is:

$ cnt = 0.085 + 0.234  \times  yr - 0.081  \times  holiday + 0.568 \times atemp - 0.124 \times windspeed + 0.087 \times season\_Summer + 0.127 \times season\_Winter + 0.054 \times mnth\_Aug + 0.104 \times mnth\_Sep - 0.246 \times weathersit\_Light $


## R2 Score

Thus, for the model with 9 variables, the r-squared on training and test data is about 79.9% and 77.5% respectively. The adjusted r-squared on the train set is about is about 79.6%

    - R-Squared for Test dataset:  0.775
    - R-Squared for Train dataset:  0.799

    - Adj. R-Squared for Test dataset:  0.765
    - Adj. R-Squared for Train dataset:  0.796

## Contact
Created by [@khatrisnk](https://www.github.com/khatrisnk) - feel free to contact me!