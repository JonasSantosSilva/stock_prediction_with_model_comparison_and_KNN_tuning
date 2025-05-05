# Stock Prediction with Model Comparison and KNN Tuning

Stock market direction prediction comparing SVM, Logistic Regression, and KNN classifiers with hyperparameter tuning on lagged returns and volume data.

## Features

- Data cleaning with missing value imputation and duplicate removal
- Label encoding for binary classification (Up/Down)
- Model comparison: SVM, Logistic Regression, KNN
- KNN hyperparameter tuning (k=1 to 300)
- Visualization of model performance metrics

## Dataset

Features used for prediction:
- `Lag1` to `Lag5`: Lagged daily returns
- `Volume`: Trading volume

Target: `Direction` (Up/Down)

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Author

**Jonas dos Santos Silva**

Electronics Engineer / Data Scientist

eng.jonas.s@gmail.com
