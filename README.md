# Phase 3 Project Description

## Business Problem
The goal of this analysis and model determine which water pumps are faulty and hence enable access to clean water across Tanzania reliably. 

## Objective
The purpose of this analysis is to use classification modeling techniques to accurately predict which water pumps are faulty and allow for stakeholders to repair/replace such and ensure a consistent supply of clean water across Tanzania.


## Data Understanding.
The dataset used in this modeling is derived from https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/25/. 
The data contain information on water pumps recorded across the country of Tanzania. The Target variable is the status group of a pump given various characteristics of the pump including but not limited to Geographic location, Water quantity, GPS height location, and Construction year among other features 

## Modeling
The modeling process involves preprocessing the data, including handling missing values, encoding categorical variables, and feature engineering. We then split the data into training and testing sets and built a multiple linear regression model to predict house prices. The model utilizes various features to make predictions and is evaluated using metrics such as R-squared to assess its performance.

## Modeling Results
Overall, The best-performing classification model is the Gradient Boosting Model with an accuracy of 80%. 
Further, the random forest model performed well with an accuracy of 78%


## Conclusion
Overall, this project demonstrates the utility of classification models in improving the predictive power of data. Classification models have allowed us to correctly predict by up to 80% if a water pump needs to be repaired. 







