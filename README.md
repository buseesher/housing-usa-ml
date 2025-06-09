# USA Housing Price Prediction with Machine Learning

This project analyzes and predicts housing prices in the USA using multiple machine learning regression techniques. It includes exploratory data analysis, feature engineering, model training, hyperparameter tuning, and performance evaluation.

## 🔍 Features

- 📊 **Exploratory Data Analysis (EDA):**
  - Univariate, bivariate, and multivariate analysis
  - Outlier detection and removal
  - Feature transformation and scaling

- 🏗 **Models Implemented:**
  - Linear Regression
  - Polynomial Regression
  - Ridge & Lasso Regression
  - Decision Tree & Random Forest
  - K-Nearest Neighbors (KNN)
  - Support Vector Regression (SVR)

- 📈 **Evaluation:**
  - MAE, MSE, RMSE, R² Score
  - Cross-validation
  - Visual comparisons of predictions vs actuals

## 📁 Dataset

The project uses the `USA_Housing.csv` dataset which includes:
- Average area income
- House age
- Number of rooms and bedrooms
- Area population
- Price
- Address

## 🛠 Requirements

- Python 3.7+
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn
- Missingno
- SciPy

Install dependencies using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn missingno scipy
  ```

## 📌 Notes

Feature scaling and log transformation are applied to improve model performance.

Hyperparameter tuning is used for Ridge, Lasso, KNN, and SVR.

Polynomial regression is optimized using degree and normalization search.
