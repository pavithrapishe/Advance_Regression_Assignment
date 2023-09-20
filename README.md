# Project Name
> Advance Regression Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Assignment Part-I
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
- You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables.
- The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.
- Assignment Part-II
4 questions that are answered in the PDF

## Conclusions
1. R2 score for both Ridge and Lasso (Test and Train) are almost same,
    Ridge (Train) : 0.948691   (Test) : 0.901582
    Lasso (Train) : 0.947310   (Test) : 0.893795
2. Top 5 significant variables using Ridge are : GrLivArea, TotalBsmtSF, 1stFlrSF, OverallQual_8, 2ndFlrSF
3. Top 5 significant variables using Lasso are : GrLivArea, TotalBsmtSF, OverallQual_8, OverallQual_9, Neighborhood_Crawfor
4. Optimal Value of lamda for Ridge : 100
5. Optimal Value of lamda for Lasso : 0.001

## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodel

## Acknowledgements
- This project was based on [Advance Regression Assignment](https://learn.upgrad.com/course/4617/segment/27466/242409/740997/3737982).


## Contact
Created by [@pavithrapishe] - feel free to contact me!
