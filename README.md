# Credit-Card-Fraud-Detection
In this project, I built a Neural Network to realize Credit Card Fraud Detection. Classic Machine Learning models are implemented as baseline models in this study. 
Baseline machine Learning models include:
### Logistic Regression
### Decision Tree
### Random Forest
### Stochastic Gradient Descent
### Gaussian Naive Bayes

## Data Explotary Analysis
* Checked the distribution of all 28 features. 
* Checked imbalanced dataset. 0.18% are fraudulent transactions. 

## Data preprocessing
I used correlation matrix to pick features. Based on the figure below, there are no duplicate features. All data should be considered.
![image](https://user-images.githubusercontent.com/55510330/171545684-54e19fd4-d875-46a4-b6f9-01aa92de8802.png)

* Train test split
* Normalized features 

## Neural Network
* To prevent overfitting, I implemented dropout layers. 
* Used binary crossentropy as loss function. 
* Used Precision, Recall, and AUC as evaluation metrics
* class_wight argument in the model 
* 

