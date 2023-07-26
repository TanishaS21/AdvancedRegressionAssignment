# Advanced Regression Assignment
> This assignment is a programming assignment wherein we have to build a Ridge and Lasso Regression model for the prediction of SalePrice of House.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
	- Which variables are significant in predicting the price of a house, and
	- How well those variables describe the price of a house.
	- Also, determine the optimal value of lambda for ridge and lasso regression.
- The company has collected a data set from the sale of houses in Australia.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The model R2-squared for Ridge and Lasso is almost the same for train and test data with Ridge performing slightly better than Lasso.
- Ridge regression does not perform feature selection and hence we have the ridge regression model with all the 221 independent variables where as Lasso Regression performs feature selection and only 70 variables out of 221 were selected here.
- The optimal value of alpha for Ridge was 10.0 and for Lasso was 0.001 .
- The top 5 features affecting the SalePrice for Ridge and Lasso Regression model are : GrLivArea, Neighborhood_Crawfor, Exterior1st_BrkFace, Functional_Typ and  Neighborhood_BrkSide.
- As the R2-squared is not varying much and Lasso Regression performs feature selection by reducing beta coefficient to 0 for certain variables, Lasso Regression model should be preferred here.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python 3.9.12
- Jupyter Notebook 6.4.8
- Anaconda Navigator 2.2.0
- numpy 1.21.5
- pandas 1.4.2
- seaborn 1.4.2
- sklearn 1.0.2
- statsmodels.api 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by Upgrad Advanced Regression Assignment module.
- Wikipedia
- Stack Overflow
- Medium
- towardsDataScience


## Contact
Created by [@TanishaS21] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->