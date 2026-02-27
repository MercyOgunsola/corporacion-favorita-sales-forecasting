# corporacion-favorita-sales-forecasting
Time-Series Sales Forecasting using XGBoost with RMSLE optimization
## Project Overview
This project develops a machine learning model to forecast daily unit sales for thousands of products across multiple stores using historical sales data.
## Dataset
Corporación Favorita Grocery Sales Forecasting (Kaggle Competition)
## Objective
This project is to develop a time-series forecasting model that predicts daily unit sales for thousands of products across multiple stores of Corporación Favorita. Using historical sales data, store and product information, and promotion details, the model aims to provide accurate sales estimates, with performance measured by the Root Mean Squared Logarithmic Error (RMSLE).
## Approach
- Data cleaning and preprocessing
- Feature engineering (date-based features, promotion indicators)
- Train-validation split
- Model training using XGBoost
- Early stopping to prevent overfitting
- Performance monitoring using RMSE
## Model Performance
- Validation RMSE: (0.53)
- Early stopping at ~550 boosting rounds
## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
## Key Takeaways
- Handling large-scale time-series retail data
- Preventing overfitting using early stopping
- Applying business-appropriate evaluation metrics (RMSLE)
