# Predicting Store Costs with Linear Regression
This project focuses on analyzing store transaction data and using a linear regression model to predict store costs. By leveraging key metrics and characteristics of stores and customer demographics, we aim to identify the factors that most influence store operating costs.

## Dataset
The dataset `(test.csv)` includes fields such as:

- Person Description: Customer demographics (e.g., marital status, education).
- Customer Order: Types of products ordered.
- Promotion Name: Promotions offered in stores.
- Store Details: Type, sales, and cost of each store.
- Weights and Recyclability: Product and packaging weights, recyclability status.

## Project Phases
1. Cleaning Phase
  - Data Inspection: Identified missing values and corrected data types.
  - Data Cleaning: Processed missing values, formatted data types, and removed unneeded columns.
2. Exploratory Data Analysis (EDA)
  - Visualizations: Used `seaborn` and `matplotlib` for visual analysis of store types, costs, and sales.
  - Statistical Analysis: Summarized key statistics with `.describe()` to understand data distributions.
3. Modeling Phase
  - Objective: Predict `Store Cost` as the target variable.
  - Model Used: Linear Regression from `sklearn.linear_model`.
  - Training and Testing:
    - Split the data using train_test_split.
    - Evaluated model performance using:
      - `r2_score` for goodness of fit.
      - `mean_squared_error` to assess prediction accuracy.
## Usage
The notebook includes:

- Data loading, cleaning, and exploration.
- Linear regression model training to predict `Store Cost`.
- Model evaluation with `r2_score` and `mean_squared_error`.

# Results
Key findings include:

- Influential factors on `Store Cost`.
- Model accuracy based on evaluation metrics.
