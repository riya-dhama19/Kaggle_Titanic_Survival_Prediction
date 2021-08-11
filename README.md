# Titanic_Survival_Prediction
Create and Train various Models which predicts whether a given passenger survived or not.

### Context 
- On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
- While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

### Objective

The Objective of Dataset is to predict whether a given passenger survived or not 

### About the dataset
- There are 1309 records and 12 attributes which are splitted in train and test set. Training set includes 819 records and 418 records are in Test Set. 
- The Survived column is Target Column. 

#### Data description :

- Survived : 0 = No, 1 = Yes
- pclass : Ticket class ie, 1 = 1st Class ( Upper ), 2 = 2nd Class ( Middle ), 3 = 3rd Class ( Lower )
- sex : 	Sex	(Gender)
- Age :	Age in years	
- sibsp	: The dataset defines family relations ( siblings / spouses aboard the Titanic ) ie, Sibling = brother, sister, stepbrother, stepsister & Spouse = husband, wife (mistresses and fiancés were ignored)
- parch	: The dataset defines family relations ( parents / children aboard the Titanic ) ie, 	Parent = mother, father & Child = daughter, son, stepdaughter, stepson
- ticket : 	Ticket number	
- fare : 	Passenger fare	
- cabin	: Cabin number	
- embarked	: Port of Embarkation ie, C = Cherbourg, Q = Queenstown, S = Southampton


#### Acknoweldgment : 
This dataset is taken from <a href="https://www.kaggle.com/c/titanic/data"> Kaggle  </a>

## Structure :

### Task 1. Collecting Data (Importing Modules and Loading Dataset)

### Task 2. Inspecting DATA

### Task 3.  Exploratory Data Analysis

### Task 4. Data Preprocessing
- Handling Missing values
- Droping irrelevent columns
- Convert categorical data into numerical form (One-Hot Encoding/Label Emcoder)

### Task 5.  Spliting Data 

### Task 6.  Applying Algorithms 
- Logistic Regression,  Decision Tree, Random Forest, Gradient Boost, XG Boost, KNN, SVM, Naive Bayes, Ada Boost,and Extra Tree

### Task 7.  Prediction on Test Data

## Conclusion 
- Gradient Boost gives the best accuracy on test dataset among all the models
- SVM gives the least accuracy on test datsset

GradientBoost is 79% accurate in predicting survival of passengers.
