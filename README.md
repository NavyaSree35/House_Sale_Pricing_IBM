# House_Sale_Pricing_IBM

## Overview

This project is part of the IBM Data Science Professional Certificate course offered by Coursera. The primary goal is to predict house sale prices using various features of the houses. This project employs data analysis and machine learning techniques to build a predictive model that can estimate the sale price of a house based on its attributes

## Table of Contents
* Introduction
* Dataset
* Features
* Tools and Libraries
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Modeling
* Evaluation
* Conclusion

## Introduction
Predicting house prices is a critical task in the real estate industry. Accurate predictions help buyers make informed decisions and sellers to set appropriate prices. This project demonstrates how machine learning algorithms can be applied to predict house prices based on historical data.

## Dataset
The dataset used in this project is provided by the IBM course on Coursera. It contains various features of houses and their corresponding sale prices. The dataset includes features such as the number of bedrooms, bathrooms, square footage of living space, lot size, and many others.

## Features
The dataset includes the following features:

* date: Date of the house sale
* price: Sale price of the house (target variable)
* bedrooms: Number of bedrooms
* bathrooms: Number of bathrooms
* sqft_living: Square footage of the living space
* sqft_lot: Square footage of the lot
* floors: Number of floors
* waterfront: Whether the house has a waterfront view
* view: Quality of the view
* condition: Condition of the house
* grade: Grade given to the house
* sqft_above: Square footage of the house apart from basement
* sqft_basement: Square footage of the basement
* lat: Latitude of the house location
* long: Longitude of the house location
* sqft_living15: Living room area in 2015
* sqft_lot15: Lot size area in 2015

## Tools and Libraries

The following tools and libraries are used in this project:
* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

## Exploratory Data Analysis (EDA)
EDA is performed to understand the distribution of the data, detect any anomalies or outliers, and identify potential relationships between features. Various visualizations such as histograms, scatter plots, and box plots are used to explore the dataset.

## Data Preprocessing
Data preprocessing steps include handling missing values, encoding categorical variables, feature scaling, and splitting the data into training and testing sets.

## Modeling
Multiple machine learning models are implemented and evaluated, including:

## Linear Regression
* Ridge Regression
* Polynomial Regression
* Hyperparameter tuning is performed using GridSearchCV to optimize the model performance.

## Evaluation
The models are evaluated using metrics such as:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

## Conclusion
The project concludes with a discussion on the model performance, insights gained from the data, and potential improvements for future work.
