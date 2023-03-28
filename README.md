# Housing Market Analysis

This repository contains a data analysis project that aims to investigate and understand the factors that influence house prices in King County, including Seattle. The dataset used in this analysis contains information on house sale prices for homes sold between May 2014 and May 2015. 

Project is from a Kaggle Competition for Housing Market Prediction
https://www.kaggle.com/datasets/harlfoxem/housesalesprediction

## Dataset and Variables

The dataset used in this analysis contains the following variables:

- `id`: a notation for a house
- `date`: date house was sold
- `price`: price is the prediction target
- `bedrooms`: number of bedrooms/house
- `bathrooms`: number of bathrooms/bedrooms
- `sqft_living`: square footage of the home
- `sqft_lot`: square footage of the lot
- `floors`: total floors (levels) in house
- `waterfront`: house which has a view to a waterfront
- `view`: has been viewed
- `condition`: how good the condition is overall
- `grade`: overall grade given to the housing unit, based on King County grading system
- `sqft_above`: square footage of house apart from basement
- `sqft_basement`: square footage of the basement
- `yr_built`: built year
- `yr_renovated`: year when the house was renovated
- `zipcode`: zip code
- `lat`: latitude coordinate
- `long`: longitude coordinate
- `sqft_living15`: living room area in 2015 (implies some renovations) this might or might not have affected the lot size area
- `sqft_lot15`: lot size area in 2015 (implies some renovations)

## Data Preprocessing

Before conducting any analysis on the data, several preprocessing steps were performed. These include handling missing values, removing duplicates, and dealing with outliers. Additionally, some variables were transformed and scaled to prepare the data for machine learning models.

## Analysis

After preprocessing the data, several exploratory data analysis techniques were used to gain insights into the relationships between the variables and the target variable, house prices. These techniques included data visualization and correlation analysis.

Several machine learning models were also developed and trained to predict house prices based on the available features in the dataset. The performance of these models was evaluated using various evaluation metrics, including mean absolute error, mean squared error, and R-squared.

## Conclusion

The results of this analysis indicate that several variables, including the square footage of the home, the number of bedrooms and bathrooms, the overall condition and grade of the house, and its location, have a significant impact on the sale price of a house in King County. Machine learning models trained on this data can be used to predict house prices with a high degree of accuracy.
