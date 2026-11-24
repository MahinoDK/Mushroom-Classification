# Mushroom-Classification
Machine learning classification of edible and poisonous mushrooms using Python and scikit-learn.
A machine learning project investigating the classification of edible and poisonous mushrooms based on their physical characteristics.

Developed as part of the Machine Learning and Machine Intelligence course at Aalborg University.

# Project Overview

The project compares three supervised machine learning algorithms using the UCI Mushroom dataset, containing 8,124 observations and 22 categorical input features.

The primary objective is to minimize false negatives, as incorrectly classifying a poisonous mushroom as edible is particularly undesirable.

# Machine Learning Methods

- Logistic Regression
- Support Vector Machine (RBF kernel)
-  Random Forest
- Hyperparameter tuning using GridSearchCV
- Five-fold stratified cross-validation
- Feature selection using chi-squared statistics
- Polynomial feature interactions
- Missing value imputation and one-hot encoding
- Results
- The selected Logistic Regression model achieved the following results on a held-out test set of 1,625 observations:

  # Metrics
  - Accuracy = 100%
  - Precision = 100&
  - Recall = 100%
  - F1-score = 100%
 These results apply to the selected dataset and do not establish reliability for real-world mushroom identification or consumption.

# Technologies

Python · scikit-learn · Pandas · NumPy · Matplotlib · Jupyter Notebook · Google Colab

# Dataset

UCI Machine Learning Repository — Mushroom Dataset
https://archive.ics.uci.edu/dataset/73/mushroom

# Methodology

The project follows the general machine learning workflow described in Chapter 2 of Aurélien Géron's Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow, 3rd edition.
