# Surprise Housing Regression Model

## General Information
The US-based housing company Surprise Housing aims to enter the Australian market by leveraging data analytics to purchase houses below their actual values and sell them for a profit. To support this endeavor, the company has collected a dataset from the sale of houses in Australia, which is provided in the CSV file. The goal is to build a regression model using regularization techniques to predict the actual value of prospective properties and make informed investment decisions.

### Business Goal
The primary objectives of the project are:
- Identify significant variables for predicting house prices.
- Assess how well these variables describe the price of a house.
- Determine the optimal values of lambda for Ridge and Lasso regression.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusions
- The regression model successfully identifies significant variables for predicting house prices, including GrLivArea, OverallQual_9, OverallQual_8, Neighborhood_Crawfor, and Exterior1st_BrkFace.
- These variables demonstrate considerable influence on house prices, with features like GrLivArea showing a 1.09 to 1.11 times increase in price per square foot.
- Optimal values of lambda for Ridge and Lasso regression are determined to be 10 and 0.001, respectively.
