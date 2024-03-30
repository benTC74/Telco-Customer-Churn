# Telco-Customer-Churn

Goal:
To create a XG Boost prediction model for customer churning for a telco company.

Dataset:
From Kaggle - https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data

Process:
- Clean the dataset with missing values and set them to 0.
- Transform the categorical features with one-hot encoding.
- Split the data for training and testing with stratification to address the issue of imbalanced dataset.
- Construct XG Boost with hyperparameters tuning.
- Evaluate the model with confusion matrix.
- Construct a single tree for further understanding of different features.
