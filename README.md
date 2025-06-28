# 🏡 Boston Housing Price Prediction

This project demonstrates the use of various regression models to predict housing prices using the Boston Housing dataset. It involves data preprocessing, exploratory data analysis, model training, evaluation, and comparison of results using multiple machine learning algorithms.

## 📘 Overview

- **Dataset Used:** Boston Housing Dataset (from `sklearn.datasets`)
- **Models Implemented:**
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- **Tech Stack:** Python, Pandas, Scikit-learn, XGBoost, Seaborn, Matplotlib

## 🔍 Objective

Predict the median value of owner-occupied homes (`PRICE`) based on features like crime rate, average number of rooms, tax rate, etc., using multiple regression techniques.

## 🛠️ Libraries Used

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost

Data Visualization
A correlation heatmap is plotted to understand relationships between features and the target.

Scatter plots of actual vs predicted values for each model help visualize performance.


Project Structure

boston-housing-price-prediction/
├── boston_price_prediction.py   # Main Python script (or .ipynb for notebook version)
├── README.md                    # Project documentation



📈 Sample Outputs
Correlation heatmap of dataset features

Evaluation metrics (MSE & R²) for:

Linear Regression

Random Forest

XGBoost

Comparison plots: Actual vs Predicted prices

🔧 Future Enhancements
Add k-fold cross-validation

Implement hyperparameter tuning with GridSearchCV

Export trained models as .pkl

Deploy with a Streamlit or Flask web app

