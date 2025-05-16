# Crop-price-prediction-using-ML
In this project, I analyzed a dataset containing crop prices and related agricultural metrics across various Indian states to predict annual crop prices using regression models. The dataset (crop_price.csv) includes 49 records with features such as cultivation cost, production yield, temperature, rainfall, and crop prices.

After verifying the data quality (no missing values or duplicates), I conducted exploratory data analysis (EDA) using histograms, scatter plots, and box plots to visualize distributions, check linear relationships, and detect outliers. This provided insights into how environmental and economic factors influence crop pricing.

I implemented and compared two regression models:

Linear Regression:

MSE: ~4.10e-30

RMSE: ~1.68e-59

MAE: ~1.24e-15

R² Score: 1.0
These near-perfect results suggest a strong linear relationship, though they may also indicate overfitting or data leakage due to the small dataset size.

Support Vector Regression (SVR):

MSE: ~0.1951

RMSE: ~0.0381

MAE: ~0.3730

R² Score: ~0.63
SVR provided a more realistic performance, showing a good fit with less risk of overfitting.
