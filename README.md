# 1. Problem Statement
Predict the estimated time a taxi takes to reach the entered location in New York City from the given data.

# 2. Dataset

## 2.1. Data collection
https://www.kaggle.com/datasets/parisrohan/nyc-taxi-trip-duration

## 2.2. Dataset shape:
729322 rows and 11 columns

## 2.3. Variable categorization:

* Continous numerical: id, pickuplongitude, pickuplatitude, dropofflongitude, dropofflatitude, trip_duration
* Discrete numerical: vendorid, passengercount
* Datetime: pickupdatetime, dropoffdatetime
* Nominal categorical: storeandfwd_flag

# 3. Files

## 3.1. eda-nyc-taxi-trip.ipynb 
* Performed Exploratory Data Analysis on the given dataset

## 3.2. FtEngineering_ModelBuilding-nyc-taxi-trip.ipynb
* Performed feature engineering on the dataset
* Built models like - Baseline model using mean, Linear Regression Model, Decision Tree Model
