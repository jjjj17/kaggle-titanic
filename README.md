First attempt using Decision Tree Classifier, limited to max depth of 5. Age NaNs were replaced with mean, and Fare NaNs were replaced with Median. 

Some data processing was done but very little feature engineering. Could use a more in-depth EDA, feature engineering and more sophisticated NaN replacement. 

Features are:
- PassengerId
- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

Initial train accuracy was 85,2% and test accuracy was 70,6%.
