# diamond-price-prediction
# Diamond Price Prediction
Predicts diamond prices from carat, cut, colour, clarity and dimensions.

- Data: seaborn "diamonds" dataset (~54k rows, public)
- Tools: Python, pandas, scikit-learn, seaborn
- Steps: data cleaning (duplicates, invalid dimensions), EDA, model comparison
- Results (80/20 test split):
  - Random Forest: R² = 0.982, RMSE = 538
  - Linear Regression: R² = 0.919, RMSE = 1129
- Run: open the notebook in Google Colab and run all cells
