
## Badges

[![Windows](https://svgshare.com/i/ZhY.svg)](https://svgshare.com/i/ZhY.svg)
[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Naereen/badges)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![CC-0 license](https://img.shields.io/badge/License-CC--0-blue.svg)](https://creativecommons.org/licenses/by-nd/4.0)
[![git](https://badgen.net/badge/icon/git?icon=git&label)](https://git-scm.com)
[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[![Visual Studio Code](https://img.shields.io/badge/--007ACC?logo=visual%20studio%20code&logoColor=ffffff)](https://code.visualstudio.com/)
[![Windows](https://badgen.net/badge/icon/windows?icon=windows&label)](https://microsoft.com/windows/)


# 💳Credit-Card-Fraud-Detection
This is a machine learning project made on Credit Card Fraud Detection. The data is taken from Kaggle. Different classification machine learning algorithms have been applied to get the maximum accuracy. 






## 🚧About Project
The purpose of the project is to make a machine learning model that will be able to detect whether the transaction made is fraud or genuine based upoen the given parameters.
The parameters used to calculate the whether the class is fraud or genuine, we are not given any information regarding the features of the dataset in order to maintain the privacy of the user.

## 📈About The Dataset
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

## 📈 Dataset Link
🏠 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
## ⬇️ Installation Guide

Install Credit Card Fraud Detection Project with git command

### Step - 1 Clone the github repository
```bash
    git clone https://github.com/coderhersh/Credit-Card-Fraud-Detection.git
```
### Step - 2 Install all required python packages
``` bash
    pip3 install pandas
    pip3 install matplotlib
    pip3 install sklearn
```

### Step - 3 Open the file
    Open project.ipynb file on jupyter notebook either on Web Browser or on VS Code.
## 🤖 Machine Learning Algorithms Used

### Logistic Regression
The method of modelling the probability of a discrete result given an input variable is known as logistic regression. The most frequent logistic regression models have a binary outcome, which might be true or false, yes or no, and so forth.
Logistic regression is a handy analysis tool for determining if a fresh sample fits best into a category in classification tasks. Because components of cyber security, such as threat detection, are classification problems, logistic regression is a valuable analytic tool.

![logistic-regression-example](https://user-images.githubusercontent.com/56130865/163219252-a8caf755-3eb7-47d4-be12-3767d75ebe12.jpg)

### Decision Trees
By constructing a decision tree, the decision tree 
classifier builds the classification model. Each node 
in the tree represents a test on an attribute, and each
 branch descending from that node represents one of the
  property's possible values. The training set's instances
 are categorised by navigating them from the root of the tree
  to a leaf, based on the results of the tests along the way.
   Each node in the tree splits the instance space into two or
more sub-spaces based on an attribute test condition, starting 
with the root node. After that, the procedure is repeated for 
the subtree rooted at the new node, until all records in the
 training set have been processed.
![decision_tree](https://user-images.githubusercontent.com/56130865/163225206-d36d03fa-4cb6-413b-b706-de39bec8cb0a.png)

### Support Vector Machine

The "Support Vector Machine" (SVM) is a supervised machine learning technique that can solve classification and regression problems. It is, however, mostly employed to solve categorization difficulties. Each data item is plotted as a point in n-dimensional space (where n is the number of features you have), with the value of each feature being the value of a certain coordinate in the SVM algorithm. Then we accomplish classification by locating the hyper-plane that clearly distinguishes the two classes.
![SVM](https://user-images.githubusercontent.com/56130865/163222622-27106d44-f14f-478a-9660-24a281fcb302.png)

### Ensemble Model
A hard voting ensemble is used in classification to predict the class with the greatest votes by aggregating the votes for crisp class labels from other models. In a soft voting ensemble, the predicted probabilities for class labels are added up and the class label with the highest sum probability is predicted.
The predictions from many models are combined in a voting ensemble. It can be used for regression or classification. In the case of regression, this entails taking the average of the models' predictions. When it comes to classification, the predictions for each label are added together, and the label with the most votes is chosen.


![majority_voting](https://user-images.githubusercontent.com/56130865/163222690-f0804689-01f3-4d34-9bf1-e456cf50068a.png)

## 📓 Authors

- [@coderhersh](https://github.com/coderhersh)


## 🚀 About Me
I'm a 4th year B.Tech CSE student currently brushing up my skills on Python and Machine Learning.

## 🌟References
1️⃣ https://www.analyticsvidhya.com/ <br/>
2️⃣ https://towardsdatascience.com/ <br/>
3️⃣ https://scikit-learn.org/stable/ <br/>
4️⃣ https://pandas.pydata.org/docs/
