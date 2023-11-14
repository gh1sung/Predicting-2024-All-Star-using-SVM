# Predicting-2024-All-Star-using-SVM
Simple implementation of SVMs to predict the potential 2024 NBA All-Stars
# NBA All-Star Prediction Using SVM

## Overview
This project employs a Support Vector Machine (SVM) to predict potential All-Star players in the NBA for the 2024 season. The model is trained on historical player performance data to identify early-season indicators of All-Star caliber performance.

## Introduction to SVM
Support Vector Machines (SVM) are a powerful class of supervised learning algorithms used for classification and regression tasks. They work by finding the hyperplane that best separates the data into classes.

## Dataset
The dataset encompasses player statistics from the 2021-2022 NBA seasons, including age, games played, wins, losses, points, field goals made, and more. The target variable is the binary `ALLSTAR` status.

## Model Training
The SVM model utilizes a radial basis function (RBF) kernel, chosen for its effectiveness with non-linear data. The training process includes scaling the features and addressing class imbalance with the Synthetic Minority Over-sampling Technique (SMOTE).

## Predictions
Predictions are made based on player performance in the early games of the 2024 season. The model is optimized for high recall to ensure minimal false negatives, with the understanding that this may increase false positives.

## Getting Started
To use this model:

1. Clone this repository.
2. Ensure Python 3 and Jupyter Notebook are installed.
3. Install required libraries: `scikit-learn`, `pandas`, `numpy`, `imbalanced-learn`.
4. Run the Jupyter Notebook to train the model and make predictions.

## Dependencies
- Python 3.x
- scikit-learn
- pandas
- numpy
- imbalanced-learn

## License
This project is open-source and available under the MIT License.

## Acknowledgements
Credit to [NBA Stats](https://www.nba.com/stats/) for providing the data used in this analysis.
