# Credit-Card-Fraud-Detection

### Project Description:
- The aim of this project is to find out whether a particular credit card transaction is a fraud or not. These kinds of projects help us to find out the probability of the customers having a fraudulent transaction.

- The dataset keeps the privacy of a customer enrolled in their bank. The transaction details have been converted into some scaled reduced features to keep the integrity of the relationship between the client and the bank.
- The dataset includes the following features: ['Time', 'V1', 'V2', 'V3', 'V4', 'V5', 'V6', 'V7', 'V8', 'V9', 'V10', 'V11', 'V12', 'V13', 'V14', 'V15', 'V16', 'V17', 'V18', 'V19', 'V20', 'V21', 'V22', 'V23', 'V24', 'V25', 'V26', 'V27', 'V28', 'Amount', 'Class'].
- All the given features are continuous.
- **Dataset link :- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud**
- <img src = "credit.jpg" style = "width:500px;height:300px"/>
### Data Description:
* It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

### Steps to follow:-

➔ Problem Understanding.

➔ Importing Libraries.

➔ Importing Dataset into Dataframes.

➔ Data Exploration.

➔ Data Cleaning (Remove irrelevant columns, missing or incorrect values).

➔ Analysing using Descriptive statistics methods.

➔ Data Visualization using interactive plots and graphs.

➔ Exploratory Data Analysis

➔ Handling an imbalanced dataset.

➔ In depth analysis of dataset.

➔ Building a model for predicting the target variable based on certain features.

➔ Evaluating a model to find out its performance.

➔ Creating more than one model and comparing them using different performance metrics.

### Result:-
	Model	Train Score	Test Score
	
6	XG Boost Classifier	99.99	99.98

1	Decision Tree		96.73	96.84

4	Ada Boost Classifier	96.61	96.61

2	Random Forest		95.60	95.70

0	Logistic Regression	94.23	94.32

5	Naive Bayes		87.57	87.63

3	Support Vector Machines	67.76	67.66


### Conclusion:-
* We just received 99.99% accuracy in our credit card fraud detection.
* Accuracy of XG Boost Classifier model is 99.99 % and Support Vector Machine Classifier not performed well.

