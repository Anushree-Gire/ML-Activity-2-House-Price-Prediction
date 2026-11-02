# ML Activity 2: Simple House Price Prediction

## Project Information
- **Subject:** Machine Learning
- **Unit:** Unit II – Supervised Learning: Regression
- **Algorithm:** Simple Linear Regression
- **Dataset:** Ames Housing Dataset

## Objective
To develop a Simple Linear Regression model that predicts house prices based on the living area of a house.

## Dataset Description
The Ames Housing Dataset contains information about residential properties in Ames, Iowa.

- **Dataset source:** [Download Ames Housing CSV](https://huggingface.co/datasets/Causal-Copilot/Causal-Copilot-Dataset/resolve/main/realworld_data/AmesHousing.csv)
- **Total records:** 2,930
- **Total columns:** 82

## Features Used
- **Input Feature (X):** `Gr Liv Area` – Above-ground living area in square feet.
- **Target Variable (y):** `SalePrice` – House selling price in dollars.

## Methodology
1. Load and inspect the dataset.
2. Select the input feature and target variable.
3. Visualise the relationship using a scatter plot.
4. Split the data into 80% training and 20% testing.
5. Train the Linear Regression model.
6. Generate predictions on test data.
7. Evaluate the model using MAE, MSE, RMSE and R².
8. Visualise actual versus predicted prices.
9. Predict the price of a new house.

## Model Evaluation

| Metric | Result |
|---|---:|
| MAE | 41,365.51 |
| MSE | 3,821,184,066.27 |
| RMSE | 61,815.73 |
| R² Score | 0.5234 |

## Conclusion
The Linear Regression model predicts house prices using living area as the input feature. It achieves an R² score of approximately 0.5234 on the test data.

However, house prices depend on several factors, such as location, quality, number of bedrooms and age. A model using only living area cannot capture all these factors.

## Files in This Repository
- `ML_Activity_2.ipynb` – Completed notebook with code, outputs and visualisations.
- `AmesHousing.csv` – Dataset used for the project.
- `README.md` – Project description and results.
