# Logistic Regression on Social Network Ads Dataset

This project implements a **Logistic Regression** model using the Social Network Ads dataset to predict whether a user will purchase a product based on their age and estimated salary. The model is trained and tested on a split of the dataset, and its performance is visualized with confusion matrices and decision boundary plots for both the training and test sets.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project demonstrates:
- Loading and preprocessing the data.
- Splitting the dataset into training and test sets.
- Applying **feature scaling** to normalize the features.
- Training a **Logistic Regression** model.
- Visualizing decision boundaries for both the training and test sets.

## Dataset
The dataset is the Social Network Ads dataset, which includes the following columns:
- **User ID**: Unique identifier for each user.
- **Gender**: Gender of the user.
- **Age**: Age of the user.
- **Estimated Salary**: Estimated salary of the user.
- **Purchased**: Whether the user purchased the product (0 or 1).

The dataset can be found on Kaggle: [Social Network Ads](https://www.kaggle.com).

## Installation
To run this code, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/logistic-regression-social-network-ads.git
   cd logistic-regression-social-network-ads
   
pip install -r requirements.txt
python logistic_regression.py

### Notes:
- Update the dataset download URL and any additional details if required.
- Add a `requirements.txt` with the necessary Python packages:
  ```text
  pandas
  matplotlib
  numpy
  scikit-learn
