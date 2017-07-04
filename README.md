# Direct Marketing Campaign Success (Banking)

Problem: A banking institution ran a direct marketing campaign based on phone calls. Often, more than one contact to the same client was required, in order to assess if the product (bank term deposit) would be subscribed or not. The task is to predict whether someone will subscribe to the term deposit or not based on the given information.

Approach:  Create and validate 3 different set of machine learning models:
#### Set 1:
1) KNeighborsClassifier
2) GaussianNB
3) LinearDiscriminantAnalysis
4) MLPClassifier
5) LogisticRegression

#### Set 2:
1) GradientBoostingClassifier 
2) AdaBoostClassifier 
3) RandomForestClassifier 
4) DecisionTreeClassifier 
5) ExtraTreesClassifier


#### Set 3: Following classifiers used Logistic regression,GaussianNB,GradientBoostingClassifier,ExtraTreeClassifier with variable weights. 
1) ExtraTreesClassifier
2) VotingClassifier 
3) StackingClassifier

- Also tried resampling techniques (smote, undersampling, oversampling etc)


## Files
- data folder includes data.csv for training and cross-validation, holdout.csv for testing and data_dictionary.txt
- main.ipynb includes all the codes for cleaning the data and models.

 
 


