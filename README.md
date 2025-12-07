# California Housing Price Prediction

**Course:** Statistical Machine Learning, AIMS  
**Author:** [Lucas Mirija RAZAFIMANANTSOA]  

## Overview
This project predicts the median house price in California using the built-in `California Housing` dataset. The analysis includes exploratory data analysis (EDA), feature engineering, and model building with both linear and non-linear methods.

## Features
- **MedInc:** Median income of the block group  
- **HouseAge:** Median age of houses  
- **AveRooms:** Average number of rooms per house  
- **AveBedrms:** Average number of bedrooms per house  
- **Population:** Number of residents in the block group  
- **AveOccup:** Average household size  
- **Latitude & Longitude:** Geographical location, transformed into `DistToCoast`  

## Model tested
- Linear Regression (with regularization)  
- Decision Tree Regressor  
- Random Forest Regressor (best-performing model)  

Hyperparameters were tuned using **Grid Search with Cross-Validation**, and model performance was evaluated using **RMSE**.
