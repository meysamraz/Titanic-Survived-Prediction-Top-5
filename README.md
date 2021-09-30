# Titanic-Survived-Prediction-Top-5
Titanic  competition use machine learning to create a model that predicts which passengers survived the Titanic shipwreck . In this notebook, I tried to understand the relationship between variables and classify who survived and  who did not . with help of  (1 - data visualization  2 - feature Engineering  3 - model building )

## Overview 
### 1) Understand the data (Shape , missing values , data types , ...)

### 2) Data Visualization  (Histograms,box plots)

### 3) Data Preprocessing and Feature Engineering

### 4) Model Building 

# Libraries used in the project

- [seaborn](https://seaborn.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [termcolor](https://pypi.org/project/termcolor/)
- [sklearn](https://scikit-learn.org/stable/)
- [xgboost](https://xgboost.readthedocs.io/en/latest/index.html)
- re

# Data Visualization 
In this part  I visualize the data to have a better understanding of the data using [matplotlib](https://matplotlib.org/), [seaborn](https://seaborn.pydata.org/)

![alt text](https://github.com/meysam810/Titanic-Survived-Prediction-Top-5/blob/master/images/age_dist.png "Passenger Age Distribution")
![alt text](https://github.com/meysam810/Titanic-Survived-Prediction-Top-5/blob/master/images/embarked_count.png "Number of passenger Survived in each Pclass")
![alt text](https://github.com/meysam810/Titanic-Survived-Prediction-Top-5/blob/master/images/fare_histogram.png "histogram of Paid Fare")

## Cleaning and  Data Preprocessing and Feature Engineering Data 

 This is the most important part of the project in my opinion, your data  can be compared to a dirty and old house that you have to clean and change its decoration and add new rooms to it , The more beautiful and new and bigger  your house is ,  higher (more accurate)  it will be sold :D 
 
 
#### 1) OneHot Encoding Gender 

#### 2) Convert Embarked into dummies

#### 3) Fill Missing Values of Cabin and categorise it better

#### 4) Convert Cabins into numbers 

#### 5) Create a new feature as FamilySize

#### 6) Drop unused columns

#### 7) Fill Missing Values of Fare

#### 8) Fill Missing Values of Age

# Building and Evaluating Model
Now it's time to sell our fresh house and our house  buyers or customers are Models  (ML algorithms) whoever offers a higher price (more accuracy) can buy the house, note that house customers based on the house (data) and house features (data features) and house usage purpose (classification or regression)

using  this algorithm :
*	[LogisticRegression](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
*	[Support vector machine](http://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
*	[K nearest neighbors](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
*	[Naive Bayes](http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html)
*	[Decision Tree](http://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html) 
*	[RandomForest](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
*	[Artificial Neural Network](https://keras.io/)
*	[GradientBoostingClassifier](http://scikitlearn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)
*	[XGBClassifier](https://xgboost.readthedocs.io/en/latest/index.html)







