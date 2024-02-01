# CAR PRICE PREDICTION REGRESSION ANALYSIS PROJECT

## Introduction
The objective of this project is to predict car prices using linear regression and hypothesis testing. By analyzing the factors that influence car prices, we aim to build a predictive model that can estimate the price of a car based on its features and specifications.

## Business Understanding
The car business in Kenya is situated at the confluence of urbanisation, economic expansion, and changing customer tastes. With more people living in cities and more people needing cars, the local automaker wants to use data to identify opportunities in the market and solve problems. In partnership with a car advisory service, the business looks for in-depth understanding of the various aspects that affect car costs.

## Problem Statetment
The local company must optimise its price based on multiple independent variables due to the intricate dynamics of the Kenyan vehicle market. The principal aim is to create a prediction model that can precisely approximate automobile prices by comprehending the correlation between car characteristics and pricing, so giving the enterprise a tactical edge in a cutthroat industry.

### Objectives
- Identify significant variables that play a role in predicting the price of a car.
- Assess the effectiveness of these variables in describing the price of a car.

## Dataset
For this analysis, we utilized the [Car Price Dataset](data/JijiCarsRawDataFinal.xlsx) available from kaggle. The dataset contains information on various car features and their corresponding prices.

## Contents of The Notebook
**1. Data Understanding and Preprocessing**
Initializes essential libraries, loads a cleaned car dataset, and outlines key features like make, year of manufacture, color, usage status, transmission type, mileage, city, and price. The 'Used' column specifies whether the car is locally used, foreign used, or brand new, with 'Price' being the target variable.

**2. Exploratory Data Analysis**
Conducts univariate analysis on categorical variables (make, color, used status, transmission, and city) using count plots. Analyzes the distribution of the target variable 'Price' through count and density plots, assessing skewness and kurtosis.

**3. Bivariate and Multivariate Analysis**
Examines the relationship between 'Price' and independent features, employing the Chi-Square Statistic for categorical variables. Prepares data for regression by encoding categorical variables and performing a log transformation on the 'Price' variable.

**4. Statistical Tests and Linear Regression**
Applies ANOVA tests to evaluate differences in mean 'Price' across car makes, colors, and mileage categories. Utilizes Pearson's Correlation Coefficient to assess the linear relationship between car color and prices. Implements a multiple linear regression model for car price prediction, evaluating performance with the Root Mean Squared Error (RMSE).







  
