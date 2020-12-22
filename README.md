# Capstone-Project

## Costa Rican Household Poverty

## Define the Problem
How can we more accurately classify the poverty levels of Costa Rican households using observeable attributes, ie education level, monthly rent, building materials, or assets, in order to predict their level of need? In order to assess the accuracy of any predictive model built, an F1 score will be used to evaluate its predictiveness.

### Identify Client
The client is the Inter-American Development Bank, who wants to assess income qualification for families in need within Costa Rica.

## Describe Dataset and How it was Cleaned/Wrangled

Dataset has 143 columns. Each record describes an individual living in Costa Rica, with attributes mostly relating to their household descriptions, education level, and location.

We filled in the missing values, combined binary columns into respective categorical columns, recoded values for easy readability, performed exploratory analysis and inferential statistics. 

We want to decide which variables to use and which to remove in order to build a classification model.

Data Cleaning
* Dealing with null values
* Finding correlations in data
* Recode values in columns for easy readability

Data Exploration
* Visualizing distribution of attributes
* Finding correlations
* Inferential statistics

Model Building
* Comparing Gradient Boosted trees
    - XGBoost
    - LightGBM
    - Ada Boost
    - Cat Boost
