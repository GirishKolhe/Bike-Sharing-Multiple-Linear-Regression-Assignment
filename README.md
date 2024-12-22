# Bike Sharing Assignment
> This assignment is a programming assignment to build a multiple linear regression model for the prediction of demand for shared bikes. 
> In the assignment, concepts such as EDA, Visualization, p-value, VIF are used.
> This uses both statsmodels and linear regression model from Scikit-learn package

## Table of Contents
* [General Info](#general-information)
* [Project Structure](#project-structure)
* [Business Context](#business-context)
* [Business Goal](#business-goal)
* [Dataset and Data Dictionary](#dataset-and-data-dictionary)
* [Model building approach](#model-building-approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- For this assignment, a Python notebook with the whole linear model, predictions, and evaluation is expected to submit
- This project aims to build and evaluate a multiple linear regression model to predict the dependent variable using several independent variables. The purpose is to understand how different features impact the target variable and to create a model that can be used for predictive analysis.

## Project Structure
- `dataset/`: Contains the dataset and data dictionary used for the analysis.
- `Bike-Sharing-Multiple-Linear-Regression-Assignment.ipynb`: Jupyter notebooks with the exploratory data analysis (EDA) and model building steps.
- `README.md`: Project documentation and overview.

## Business Context
- Bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 
- The company is finding it very difficult to sustain in the current market scenario. 
- So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

## Business Goal
- To model the demand for shared bikes with the available independent variables. 
- It will be used by the management to understand how exactly the demands vary with different features. 
- They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
- Further, the model will be a good way for management to understand the demand dynamics of a new market

## Dataset and Data Dictionary
The following files are present inside dataset folder:
- day.csv (dataset)
- Readme.txt (data dictionary)

## Model building approach
> At high level this assignment is divided into 9 steps:
- Importing and understanding data
- Visualizing the Data - numerical and categorical variables
- Data preparation - includes choice between Binary Encoding and One-Hot encoding, inferences
- Splitting the data into training and testing set
- Rescaling the features
- Building a linear model - includes comparison between various models
- Residual Analysis of the train data
- Making predictions using final model
- Model Evaluation
- Recommendation and Model Summary

## Conclusions
A final model with following key predictors :
- **yr** : Reflects the yearly trend and is highly significant.
- **workingday** : Indicates whether the day is a working day, significant for demand fluctuations.
- **temp** : Temperature, a strong predictor of bike rentals.
- **Spring and Winter** : Season, significant for seasonal variations.
- **Showers** : Weather condition, important for understanding how different weather affects demand.
- **Sunny** : Another weather condition, significant for the model.
- **month_9** : Month indicators capturing seasonal trends.
- **Monday** : Day of the week, significant for weekly trends.

## Technologies Used
- Python - version 3.12.4
- Matplotlib - version 3.8.4
- Numpy - version 1.26.4
- Pandas - version 2.2.2
- Seaborn - version 0.13.2
- Statsmodels - version 0.14.2
- Scikit-learn - version 1.4.2

## Acknowledgements
- Upgrad Team and instructors

## Contact
Created by [@GirishKolhe] - feel free to contact us!