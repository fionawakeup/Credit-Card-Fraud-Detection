# Credit-Card-Fraud-Detection
In this project, I built a Neural Network to detect credit card fraudulent transactions. Classic Machine Learning models are implemented as baseline models in this study. 
Baseline machine Learning models include:
* Logistic Regression
* Decision Tree
* Random Forest
* Stochastic Gradient Descent
* Gaussian Naive Bayes

The dataset contains 280,000+ transactions with labels and each transaction has 28 features. 

## Data Explotary Analysis
* Checked distribution of all 28 features. 
* Checked imbalanced dataset. 0.18% are fraudulent transactions. 

## Data preprocessing
* Used correlation matrix to pick features. As shown the plot below, there are no duplicate features, so all data should be considered.
![image](https://user-images.githubusercontent.com/55510330/171545684-54e19fd4-d875-46a4-b6f9-01aa92de8802.png)

* Train test split
* Normalization

## Machine Learning Modeling
* To prevent overfitting, I implemented dropout layers in Neural Network. 
* Used binary crossentropy as loss function in Neural Network. 
* Used Precision, Recall, and AUC as evaluation metrics.
* class_weight argument in Neural Network to deal with imbalanced dataset. 
* To handle imbalanced dataset in baseline machine learning models:
  * Used resample from Sklearn to upsample minority.
  * Used resample from Sklearn to downsample majority. 
  * Generated synthetic samples by SMOTE from imblearn.

## Prediction results
![ff0fa37210f74e88e58af6ca61fe9b7](https://user-images.githubusercontent.com/55510330/171550351-17c077e9-6e8f-42d5-bfed-8ce382eae4c1.png)
