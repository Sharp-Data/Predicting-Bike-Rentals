# Project: Predicting Bike Rentals


### Overview

In cities across the US, bike sharing programs are becoming increasingly popular.  Anyone can rent a bike by the hour or by the day from any of the communal bike sharing stations.  Washington D.C. has one of these programs.  Hadi Fanaee-T (http://www.liaad.up.pt/area/fanaee) at the University of Porto compiled this data into a CSV file, which contains 17,380 rows.  Each row represents the bike rental count "cnt" for a single hour of a single day.


We will be trying to predict the bike rental count for one hour time periods using the following models to see which one is most accurate:

- Linear Regression
- Decision Tree
- Random Forest

### Results

We were able to reduce our error metric (mean squared error) from ~17,054 with a linear regression model to ~2,149 with Random Forest.

### Files & Data

- *PBR.ipynb - Code in Jupyter Notebook*
- *bike_rental_hour.csv - Cleaned dataset which contains the bike rental count "cnt" for a single hour of a single day.*
