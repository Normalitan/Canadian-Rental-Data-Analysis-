## Regression Analysis on Canadian Rental Data

#Overview
This project focuses on predicting rental prices in Canadian cities using several regression models. The analysis encompasses data cleaning, exploratory data analysis (EDA), and model evaluation using various regression techniques, including Linear Regression, Ridge, Lasso, ElasticNet, and Polynomial Regression.

# Dataset
The dataset includes rental listings from various Canadian cities, featuring attributes such as city, lease term, property type, bedrooms, square footage, furnishing status, and rental price (target variable).

# Objectives
1. EDA: Perform EDA to explore feature distributions, correlations, and identify any data quality issues.
2. Data Cleaning: Handle missing values and prepare the dataset for modeling.
3. Modeling: Apply different regression models to predict rental prices, including Linear Regression, RidgeCV, LassoCV, ElasticNetCV, and Polynomial Regression.
4. Model Evaluation: Use metrics like RMSE, MSE, and R^2 to evaluate model performance and select the best model.

# Methods
- EDA: Utilized visualizations to explore data distribution and detect outliers that could impact the target variable.
- Data Cleaning: Addressed missing values and ensured categorical variables were encoded and standardized for consistency.
- Feature Engineering: Applied One-Hot Encoding for categorical variables and standardized numerical features.
- Modeling: Implemented RidgeCV, LassoCV, ElasticNetCV, and ultimately Polynomial Regression models using cross-validation for parameter tuning. Combined training and validation sets to build the final models and predicted on the test set.
- Model Evaluation: Compared models using RMSE, MSE, and R^2 metrics to determine the top performer for this dataset.

# Results
Ridge and Lasso models performed similarly with ElasticNetCV slightly underperforming. Polynomial regression added complexity and managed to fit the data well.

# Conclusion
The project demonstrates the effectiveness of different regression models in predicting rental prices.
