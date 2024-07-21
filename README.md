# Classification On Academic Success Dataset - Kaggle

## Description
This repository contains a LightGBM classification model developed to classify instances into three categories: "Dropout", "Enrolled", and "Graduate." The model is trained on a dataset with features that are used to predict the target variable. The project includes data preprocessing, model training, evaluation, and submission of predictions.

## Project Structure
-classtrain.csv: Training dataset used to train the model.

-classtest.csv: Test dataset used to generate predictions.

-final.csv: Final submission file with predictions for the test set.

-notebooks/: Directory containing Jupyter notebooks with exploratory data analysis (optional).

-src/: Directory containing Python scripts for data preprocessing, model training, and evaluation (optional).

## Requirements
-numpy

-pandas

-matplotlib

-seaborn

-scikit-learn

-lightgbm

-scipy

## Usage
-Data Preparation: Load your training and test data using the provided CSV files.

-Model Training: The script trains a LightGBM classifier using 10-fold cross-validation.
Hyperparameters for the model are defined in the params dictionary.
Evaluation:

-The model's performance is evaluated based on accuracy on both training and validation datasets.
Prediction:

-After training, the model predicts on the test dataset, and the results are saved in final.csv.

## Acknowledgements
LightGBM Documentation (https://lightgbm.readthedocs.io/en/stable/)
Scikit-learn Documentation (https://scikit-learn.org/0.21/documentation.html)
