# Credit-Card-Fraud-Detection
In this project, I built a Neural Network to realize Credit Card Fraud Detection. Classic Machine Learning models are implemented as baseline models in this study. 
Baseline machine Learning models include:
### Logistic Regression
### Decision Tree
### Random Forest
### Stochastic Gradient Descent
### Gaussian Naive Bayes

## Data Explotary Analysis
* Checked distribution of all 28 features. 
* Checked imbalanced dataset. 0.18% are fraudulent transactions. 

## Data preprocessing
* Used correlation matrix to pick features. As shown the plot below, there are no duplicate features. All data should be considered.
![image](https://user-images.githubusercontent.com/55510330/171545684-54e19fd4-d875-46a4-b6f9-01aa92de8802.png)

* Train test split
* Normalization

## Neural Network
* To prevent overfitting, I implemented dropout layers. 
* Used binary crossentropy as loss function. 
* Used Precision, Recall, and AUC as evaluation metrics
* class_weight argument in the model to deal with imbalanced dataset. 
* 

