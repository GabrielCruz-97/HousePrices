### HousePrices

Repository created for the [Kaggle competition ](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview) on house price prediction in Ames, Iowa (United States).


![title](images/cover.png)

## Step 1: First Model

- In this stage, we performed only the basics to check the results without any data preprocessing or feature engineering.
- To simplify:
  - All missing values were replaced with `-1`.
  - All text columns were removed.
- We built models using three algorithms:
  - **Linear Regression**
  - **Decision Tree Regressor**
  - **KNeighborsRegressor**
- The results were evaluated using:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)** (preferred, as it was the criterion used in the competition).
- **Public score returned by Kaggle:** `0.25476`
