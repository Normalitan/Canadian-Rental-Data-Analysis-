## Regression Analysis on Canadian Rental Data

# Overview
This project focuses on predicting housing prices using three different regression models: RidgeCV, LassoCV, and ElasticNetCV Regression. Involves data preprocessing, model training, and evaluation using various regression techniques to determine the most accurate model for predicting housing prices.

# Dataset
The dataset contains information on housing features such as square footage, number of baths, city-specific dummy variables, and more. The target variable is the price of the house.

# Objectives
EDA: Perform Exploratory Data Analysis to understand the distribution of housing prices and relationships between features.
Modeling: Apply and compare three regression models: RidgeCV, LassoCV, and ElasticNetCV to predict housing prices.
Model Evaluation: Evaluated performance using Mean Squared Error (MSE) and R-squared error (R^2) to identify the best-performing model.

# Methods
EDA: Conducted exploratory analysis to visualize the distribution of key features and their relationships with the target variable, including identifying any missing values.
Modeling: Implemented RidgeCV, LassoCV, and ElasticNetCV regression models. Hyperparameter tuning was performed to optimize the model parameters for better accuracy.
Model Evaluation: Compared models using MSE and R^2 to determine the most effective model for predicting housing prices.
Visualization: Created visualizations to show the actual vs. predicted prices for each regression model using a 1x3 subplot format.

# Results
Ridge Regression: Achieved a Root Mean Squared Error (RMSE) of 455.03 and an R-Squared (R^2) of 0.70 with the best alpha value of 0.1, indicating a strong fit to the data.
Lasso Regression: Achieved a Root Mean Squared Error (RMSE) of 456.52 and an R-Squared (R^2) of 0.70 with the best alpha value of 0.1, showing a comparable performance to Ridge Regression.
ElasticNet Regression: Achieved a Root Mean Squared Error (RMSE) of 505.00 and an R-Squared (R^2) of 0.63, indicating a slightly lower performance compared to Ridge and Lasso Regression models.
The Ridge Regression model demonstrated the best performance with the lowest RMSE, indicating it is the most accurate model for predicting housing prices in this dataset.

# Conclusion
This project highlights the effectiveness of using various regression techniques to predict housing prices. The application of feature engineering, hyperparameter tuning, and thorough model evaluation was crucial in identifying the most suitable model. The Ridge Regression model emerged as the top performer, providing the most accurate predictions with the lowest RMSE. It is recommended for deployment in scenarios that require reliable and precise housing price predictions.

