# Credit Risk Analysis
* This is the repository for Credit Risk Analysis Machine Learning Project where we build a classifier that can efficiently identify bad loans.
* We used the German Credit Risk data from Kaggle https://www.kaggle.com/kabure/german-credit-data-with-risk
* Here we did Exploratory Data Analysis of this dataset from different perspectives to know in-detail about the persons's bad and good risks.
* For our model building we used are Logistic Regression, Support Vector Machine, K-Nearest Neighbors, Random Forest Classifier using GridsearchCV and Gaussian Naive Bayes.


## EDA & Feature Engineering
* We analyzed and fill the missing value of this dataset so it can be usable for our model.
* We simplified our data in the perspective of Job Categories and encoded Risk as 1 for bad and 0 for good.
* Analyzed different value counts, by plotting graphs and also through pivot table.
* We generated dummies for our categorical variables


## Data Cleaning and Exploratory Data Analysis
* We analyzed and cleaned this dataset so it can be usable for our model.
* And in EDA part, we simplified our data and analyzed different value counts through graphs also through pivot table


## Model Building
* We split this dataset into test and train set with 20% test set.
* We used different Models and evaluated on the basis of recall.
* The Gaussian Naive Bayes model gave us the best recall than the other approaches on the test set.

Model Used | Recall | Accuracy Score
------------ | ------------- | -------------
Gaussian Naive Bayes | 0.58 | 65.5%
Random Forest Classifier | 0.46| 74%
Logistic Regression | 0.41 | 75.5%
K-Nearest Neighbors | 0.27 | 67%
Support Vector Machine | 0.14 | 71.5%
