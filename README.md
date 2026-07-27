# Gold Price Prediction with Machine Learning

This project builds a machine learning regression model to predict gold prices using historical market data. The workflow is implemented in a Jupyter Notebook and uses a Random Forest Regressor to learn patterns from financial indicators such as the S&P 500, oil prices, silver prices, and the EUR/USD exchange rate.

## Project Overview

The goal of this project is to estimate the future value of gold based on historical features from the dataset. It includes:

- Data loading and preprocessing
- Exploratory data analysis and correlation checks
- Feature/target splitting
- Model training and evaluation
- Visualization of actual versus predicted prices

## Dataset

The project uses the file:

- [gld_price_data.csv](gld_price_data.csv)

This dataset contains daily market values including:

- Date
- SPX
- GLD
- USO
- SLV
- EUR/USD

## Methodology

The notebook follows these steps:

1. Load the dataset into a Pandas DataFrame
2. Inspect rows, columns, missing values, and descriptive statistics
3. Analyze correlations between financial features and gold prices
4. Split the data into training and testing sets
5. Train a Random Forest Regressor
6. Evaluate performance using the R-squared metric
7. Visualize the prediction results

## Model

- Model type: Random Forest Regressor
- Library: scikit-learn
- Evaluation metric: R-squared ($R^2$)
- Result achieved in the notebook: approximately 0.9894 on the test set

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Setup

Install the required dependencies:

```bash
pip install jupyterlab pandas numpy matplotlib seaborn scikit-learn
```

## How to Run

1. Open the project folder in VS Code or Jupyter
2. Launch the notebook:

```bash
jupyter notebook
```

3. Open [goldPricePrediction.ipynb](goldPricePrediction.ipynb) and run the cells in order

You can also view the static project summary in [index.html](index.html).

## Project Files

- [goldPricePrediction.ipynb](goldPricePrediction.ipynb) — main Jupyter notebook with the full workflow
- [gld_price_data.csv](gld_price_data.csv) — historical gold price dataset
- [index.html](index.html) — interactive HTML summary of the project
- [README.md](README.md) — project documentation

## Notes

This is an educational machine learning project and should not be treated as financial advice. The model is intended for learning and experimentation rather than real-world trading decisions.
