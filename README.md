# House Price Prediction Using Machine Learning

## Project Overview
This project aims to predict house prices using machine learning techniques based on various housing features such as area, bedrooms, bathrooms, floors, year built, location, condition, and garage availability.

## Dataset Features
- Area
- Bedrooms
- Bathrooms
- Floors
- Year Built
- Location
- Condition
- Garage

## Algorithms Used
- Linear Regression
- Random Forest Regression

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results

| Model | MAE | RMSE | R² Score |
|---------|---------|---------|---------|
| Linear Regression | 244003.46 | 280469.74 | -0.0111 |
| Random Forest Regression | 247599.77 | 287304.25 | -0.0610 |

## Conclusion
Linear Regression performed slightly better than Random Forest Regression on the given dataset. However, both models showed limited predictive performance due to weak correlations between the input features and house prices.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
