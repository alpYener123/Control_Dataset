# Control Dataset Experiment

This repository contains a synthetic control dataset experiment testing whether lasso produces sparse coefficient vectors, unlike ridge regression.

This is to test the hypothesis coming from Tibshirani’s original lasso paper, “Regression Shrinkage and Selection via the Lasso”, that lasso tends to produce exact-zero coefficients, while ridge regression shrinks coefficients but generally does not remove them.

## Files

- `experiment.ipynb`: generates the dataset and runs the lasso/ridge comparison.

## Dataset

The dataset has 5,000 samples and 100 Gaussian features. Only 10 features determine the label. The remaining 90 have true coefficient zero.

## Environment

- Python 3.13.5
- numpy 2.4.2
- pandas 3.0.3
- scikit-learn 1.8.0
- conda environment

## Run

Simply run the notebook.
