# ML Activity 2: Simple House Price Prediction

## Project Information

- **Subject:** Machine Learning
- **Unit:** Unit II – Supervised Learning: Regression
- **Algorithm:** Simple Linear Regression
- **Dataset:** Ames Housing Dataset
- **Platform:** Google Colab

## Objective

To develop a Simple Linear Regression model that predicts house prices based on the above-ground living area of a house.

## Dataset Description

The Ames Housing Dataset contains information about residential properties in Ames, Iowa.

- **Dataset Source:** [Ames Housing Dataset – CSV](https://huggingface.co/datasets/Causal-Copilot/Causal-Copilot-Dataset/resolve/main/realworld_data/AmesHousing.csv)
- **Original Dataset Records:** 2,930
- **Original Dataset Columns:** 82
- **Prepared Dataset Records:** 2,930
- **Prepared Dataset Columns:** 2

The prepared dataset contains only the selected feature and target variable, with missing values removed.

## Features Used

- **Input Feature (X):** `Gr Liv Area` – Above-ground living area in square feet.
- **Target Variable (y):** `SalePrice` – House selling price in dollars.

## Methodology

1. Load and inspect the Ames Housing dataset.
2. Explore the dataset using basic data analysis.
3. Select the input feature and target variable.
4. Handle missing values in the selected columns.
5. Visualise the relationship using a scatter plot.
6. Split the data into 80% training and 20% testing.
7. Train the Simple Linear Regression model.
8. Generate predictions on test data.
9. Evaluate the model using MAE, MSE, RMSE and R² score.
10. Visualise actual versus predicted prices.
11. Predict the price of a new house using its living area.

## Linear Regression Model

The model produces the following equation:

**SalePrice = 19,250.56 + (106.73 × Gr Liv Area)**

- **Intercept:** 19,250.56
- **Coefficient:** 106.73

## Model Evaluation

The model was evaluated using the test dataset.

| Metric | Result |
|---|---:|
| MAE | 41,365.51 |
| MSE | 3,821,184,066.27 |
| RMSE | 61,815.73 |
| R² Score | 0.5234 |

## Conclusion

The Simple Linear Regression model predicts house prices using the above-ground living area as the input feature. It achieved an R² score of approximately 0.5234 on the test data.

The results indicate that living area has a relationship with house prices. However, house prices also depend on other factors such as location, quality, number of bedrooms and age of the property. Therefore, using only one feature limits the model's prediction accuracy.

## Files in This Repository

- `Ml_Activity_2 (1).ipynb` – Completed notebook containing code, outputs and visualisations.
- `AmesHousing.csv` – Original Ames Housing dataset.
- `ames_housing_prepared.csv` – Cleaned dataset containing the selected feature and target variable.
- `README.md` – Project description, methodology and model results.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
