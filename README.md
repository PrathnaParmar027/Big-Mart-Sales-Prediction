# Big Mart Sales Prediction

## Project Overview

This project predicts product sales at Big Mart outlets using machine learning.

The project uses an XGBoost Regression model to predict `Item_Outlet_Sales`.

## Objective

- Analyze Big Mart sales data.
- Handle missing and categorical data.
- Build an XGBoost regression model.
- Evaluate the model using R² score.

## Dataset

- Training records: 8,523
- Input features: 11
- Target: `Item_Outlet_Sales`
- Training data: `Train.csv`
- Testing data: `Test.csv`

## Data Preprocessing

- Missing `Item_Weight` values were filled using the mean.
- Missing `Outlet_Size` values were handled based on `Outlet_Type`.
- Categorical features were converted using Label Encoding.
- Data was divided into 80% training and 20% testing sets.

## Model

**XGBoost Regressor (XGBRegressor)**

The model predicts numerical sales values based on product and outlet features.

## Results

| Dataset | R² Score |
|---|---:|
| Training | 0.8751 |
| Testing | 0.5156 |

**Test R² Score: 0.5156**

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Project Files

- `Big_Mart_Sales_Prediction.ipynb` — Complete Jupyter Notebook
- `Big-Mart-Sales-Prediction.pptx` — Project presentation
- `Train.csv` — Training dataset
- `Test.csv` — Testing dataset

## How to Run

1. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
2. Keep `Train.csv` and `Test.csv` in the same working environment.
3. Run the notebook cells in order.

## Disclaimer

This project is developed for educational and internship purposes. The predictions depend on the dataset and preprocessing used.
