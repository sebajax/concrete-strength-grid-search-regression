# 🍏 Concrete Strength Prediction

This repository contains the work done to predict the compressive strength of concrete using regression models, including **Decision Tree Regressor** and **Support Vector Regression (SVR)**. **Grid Search** was employed for hyperparameter optimization, enhancing the performance of these models.

## Project Description

The primary goal of this project is to predict the compressive strength of concrete based on various features such as the amount of cement, water, admixtures, and other components. Different regression models were used, and their hyperparameters were optimized to improve the accuracy of the predictions.

## Project Structure

- `data/`: Contains the dataset used for training and evaluating the models.
- `notebooks/`: Jupyter Notebooks with exploratory data analysis (EDA), model training, and hyperparameter tuning.
- `models/`: Scripts and definitions of the regression models used.
- `results/`: Stores the results of model evaluations and performance metrics.

## Models Used

### 1. Decision Tree Regressor
- **Original Performance**:
  - MSE: 97.50
  - RMSE: 9.87
  - MAE: 7.63
  - R²: 0.63

- **After Grid Search**:
  - MSE: 80.90
  - RMSE: 9.87
  - MAE: 6.48
  - R²: 0.70

### 2. Support Vector Regression (SVR)
- **Original Performance**:
  - MSE: 213.88
  - RMSE: 14.62
  - MAE: 12.01
  - R²: 0.19

- **After Grid Search**:
  - MSE: 86.13
  - RMSE: 9.87
  - MAE: 7.10
  - R²: 0.68

## Conclusion

The Grid Search hyperparameter tuning has significantly improved the performance of both models, especially SVR, which went from a very low initial performance to a much more accurate and explanatory model. The Decision Tree Regressor also showed notable improvements with reduced errors and increased determination coefficients. These results highlight the importance of hyperparameter optimization in enhancing the performance and predictive capability of machine learning models.
