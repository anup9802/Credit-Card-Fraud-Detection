# Credit-Card-Fraud-Detection
The problem statement chosen for this project is to predict fraudulent credit card transactions with the help of machine learning models.

In this project, we will analyse customer-level data which has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group. 

The dataset is taken from the Kaggle website (https://www.kaggle.com/mlg-ulb/creditcardfraud) and it has a total of 2,84,807 transactions, out of which 492 are fraudulent. Since the dataset is highly imbalanced, so it needs to be handled before model building.

Several ML alogorithms have been applied (with and without over/under sampling) and the best result got using XGBoost with oversampled data:
Accuracy in the train dataset - 0.9963860506832211
Accuracy in the test dataset - 0.9928197745865665
ROC AUC in train dataset - 0.9995835772061725
ROC AUC in test dataset - 0.9964037000562745
