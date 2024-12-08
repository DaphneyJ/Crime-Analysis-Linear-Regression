# US Crime Analysis with Custom Linear Regression

This repository contains a full analysis of U.S. crime data where I analyze crime and take a closer look at how socioeconomic factors and demographic factors influence crime rates. My project includes exploratory data analysis, data cleaning, feature engineering, and model implementation in Python. What makes this analysis unique is that I built my own linear regression model from scratch and compared it with Scikit-Learn's implementation. This project has been a great learning experience, and I’m excited to share it.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Description](#data-description)
3. [Features of the Project](#features-of-the-project)
4. [Steps](#steps)
5. [Results and Insights](#results-and-insights)


---

## Project Overview
The goal of this project is to explore the relationships between crime rates and various demographic and socioeconomic factors. My project aims to answer some key questions:
- How do factors like population, income, and education impact crime rates?
- Which features are most strongly correlated with crime?
- Can we predict crime rates using a regression model?
- Are there clear patterns between violent and non-violent crimes?

## Data Description
The dataset contains crime statistics from various U.S. communities, downloaded from [Kaggle](https://www.kaggle.com/). The data includes:
- **Demographics**: race distribution, income, unemployment, education.
- **Crime Stats**: violent and non-violent crimes per population.
- **Socioeconomic data**: population size, poverty rates, education levels, median income, and more.

The dataset was cleaned and processed to handle missing values, reduce dimensionality, and preapre it for analysis.

## Features of the Project
- **Custom Linear Regression Model**: Built from scratch using the Normal Equation (math meets coding!). Included a comparison with Scikit-Learn's implementation.
- **Exploratory Data Analysis**:
  - Used visuals like heatmaps, bar charts, and scatterplots to uncover trends.
  - Analyzed correlations to identify relationships between features.
- **Feature Engineering**:
  - One hot encoding for categorical variables.
  - Log transformation of target veriable and scaling to improve model performance.
- **Model Evaluation**:
  - Metrics like R², Adj R², Mean Squared Error, and Mean Absolute Error to validate my models

## Steps
1. **Data Preprocessing**:
   - Handled missing data (by imputation or removal) and removed irrelevant features.
   - Ensured consistent data types
   - Converted categorical variables into numerical using one-hot encoding.
2. **EDA**:
   - Created visuals to understand the data better.
   - Analyzed correlations between factors and crime rates.
3. **Model Building**:
   - Implementation of linear regression model using the Normal Equation.
   - Compared with Scikit-Learn’s model for accuracy.
4. **Model Evaluation**:
   - Identified key predictors of crime.
   - Interpreted coefficients and significance of predictors.
   - Analyzed patterns in violent vs. non-violent crimes.

## Results and Insights
- **Key Drivers of Crime**:
  - Higher population and poverty levels are strongly correlated with increased crime rates.
  - Lower income and education levels are associated with higher crime rates.
- **Model Performance**:
  - Custom linear regression model achieved a high R², indicating strong predictive capabilities.
  - Scikit-Learn's Linear Regression model provided similar performance, validating my custom model implementation.

To see the full detailed analysis including all the steps, visuals, and explanations, open the `crime_data_analysis.ipynb` file in the repository. It walks you through my process from data cleaning to modeling, with written insights and observations at every stage.

