# US Crime Analysis with Custom Linear Regression

This repository contains a full analysis of U.S. crime data, focusing on identifying key socioeconomic and demographic factors that influence crime rates. My project includes exploratory data analysis, data cleaning, feature engineering, and a custom implementation of linear regression from scratch. This analysis also answers specific research questions about crime patterns.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Description](#data-description)
3. [Features of the Project](#features-of-the-project)
4. [Steps](#steps)
5. [Results and Insights](#results-and-insights)


---

## Project Overview
The goal of this project is to explore the relationships between crime rates and various demographic and socioeconomic factors. Through data analysis and modeling, my project aims to answer questions such as:
- How do factors like population, income, and education impact crime rates?
- What features are most strongly correlated with crime?
- Can we predict crime rates based on these features?
- Are there distinguishable patterns between violent and non-violent crimes?

## Data Description
The dataset contains crime statistics from various U.S. communities, downloaded from [Kaggle](https://www.kaggle.com/). The data includes:
- **Demographic features**: race distribution, income, unemployment, education.
- **Crime metrics**: violent and non-violent crimes per population, and crime categories.
- **Socioeconomic factors**: poverty rates, population size, unemployment, and median income.

The dataset was cleaned and processed to handle missing values, reduce dimensionality, and preapre it for analysis.

## Features of the Project
- **Custom Linear Regression Model**: Built from scratch using the Normal Equation. Included a comparison with Scikit-Learn's implementation.
- **Exploratory Data Analysis**:
  - Visualizations of crime rates and patterns.
  - Correlation heatmaps to identify relationships between features.
- **Feature Engineering**:
  - One hot encoding for categorical variables.
  - Log transformation of target veriable and scaling for improved model performance.
- **Model Evaluation**:
  - Validation Metrics used: R², Adj R², Mean Squared Error, and Mean Absolute Error.

## Steps
1. **Data Preprocessing**:
   - Cleaning missing data and removing irrelevant features.
   - Converting categorical variables into numerical using one-hot encoding.
2. **EDA**:
   - Insights into crime patterns by state and demographic factors.
   - Analysis of correlations between socioeconomic factors and crime rates.
3. **Model Building**:
   - Implementation of linear regression using the Normal Equation.
   - Comparison with Scikit-Learn's Linear Regression model.
4. **Model Evaluation**:
   - Metrics calculated.
   - Interpretation of coefficients and significance of predictors.

## Results and Insights
- **Key Drivers of Crime**:
  - Higher population and poverty levels are strongly correlated with increased crime rates.
  - Lower income and education levels are associated with higher crime rates.
- **Model Performance**:
  - Custom linear regression model achieved a high R², indicating strong predictive capabilities.
  - Scikit-Learn's Linear Regression model provided similar performance, validating my custom model implementation.

