# -New-York-City-travel_fare-prediction

## Overview
This project builds a machine learning model to predict taxi fares in New York City. Using features like pickup/drop-off location, time, and passenger count, the model aims to provide accurate fare estimates, leveraging a dataset from Kaggle.

## Features
- **Data Preprocessing**: Handling missing values, feature engineering, and scaling.
- **Exploratory Data Analysis (EDA)**: Insights into location trends, fare distributions, and more.
- **Machine Learning**: Training a regression model to predict fares.
- **Model Evaluation**: Accuracy, RMSE, and feature importance analysis.

## Dataset
The dataset is from the [Kaggle NYC Taxi Fare Prediction Competition](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction). It includes:
- Pickup/drop-off latitude and longitude
- Passenger count
- Timestamp of the ride
- Taxi fare (target variable)

### Data Preprocessing
1. **Feature Engineering**:
   - Extracting hour, day, and weekday from timestamps.
   - Calculating distances between pickup and drop-off locations.
2. **Cleaning**:
   - Removing outliers and handling missing values.
3. **Scaling**:
   - Normalization of continuous variables.

## Requirements
Install the required dependencies using:
```bash
pip install -r requirements.txt
