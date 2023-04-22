# Mushroom_Classification Repository!
## About
This is our Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on classifying a mushroom's edibility based off its features. We used the the dataset titled [Mushroom Edibility Classification](https://www.kaggle.com/datasets/devzohaib/mushroom-edibility-classification?resource=download&select=secondary_data.csv). You may view the full notebook [here.](https://github.com/LeQi008/Mushroom_Classification/blob/main/Mushroom_Classification.ipynb) 

Or you may view the source code in order from:

1. [Data Preparation & Cleaning](https://github.com/LeQi008/Mushroom_Classification/blob/main/1_Data_Preparation_%26_Cleaning.ipynb)
    1. Proper renaming of features
    2. Dealing with NaN values
2. [Data Exploration and Visualisation](https://github.com/LeQi008/Mushroom_Classification/blob/main/2_Data_Exploration_%26_Visualisation.ipynb)
    1. Numerical Variables
    2. Categorical Variables
    3. Cramer's V
3. [Machine Learning Models](https://github.com/LeQi008/Mushroom_Classification/blob/main/3_Machine_Learning_Models.ipynb)
    1. Naives Bayes 
    2. Logistic Regression
    3. Decision Tree
4. [Optimisation](https://github.com/LeQi008/Mushroom_Classification/blob/main/4_Optimisation.ipynb)
    1. Feature Importance
    2. Support Vector Machines
    3. Hyperparameter Tuning



## Contributors
- @LeQi008 - Data Cleaning, Data Exploration, Decision Tree, Optimisation
- @shufang17 - Data Cleaning, Logistic Regression, Optimisation
- @abigaildu - Data Cleaning, Naives Bayes, Optimisation

## Motivation
Mushroom hunting (otherwise known as "shrooming") is enjoying new peaks in popularity. It is a popular pasttime for people who enjoy searching for edible or medicinal mushrooms in the wild. Once a mushroom is collected, it needs to be properly identified and prepared before consumption. We therefore hope to create a model to help predict if a mushroom is edible.

## Problem Definition
- We seek to understand the relationships between a mushroom's features and its edibility.
- Are we then able to create a reliable model to predict if a mushroom is edible based of its features?

## Models Used
1. Naïve Bayes 
2. Logistic Regression
3. Decision Tree 
4. Support Vector Machines

## Conclusion
- Most features of a mushroom did not seem to have any clear correlation to the edibility of a mushroom. But when inputted into certain Machine Learning Models, the combination of these features can produce a fairly reliable prediction. 
- Features of a mushroom are likely to have non-linear relationships with each other. 
- The Naïve Bayes Model and Logistic Regression Model did not work well when fed variables with non-linear relationships. 
- The Decision Tree and Support Vector Machine Model with RBF kernel worked exceptionally well when fed with non-linearly related variables. They had high accuracies in predicting edibility of a mushroom while having a very high TPR and a very low FPR. 
- In conclusion, with the right models and sufficient combinations of features, it is indeed possible to predict if a mushroom is edible or not with a great amount of accuracy based off the mushroom's features.

## What did we learn from this project?
- Cramer's V for nominal features
- Visualising probability distribution using ROC
- Naïve Bayes Model
- Logistic Regression Model
- Tuning depth of Decision Tree Model
- Support Vector Machines
- Feature Importance
- Hyperparameter Tuning using GridSearchCV
- Collaborating using GitHub


## References
Cramer's V : <br />
  https://www.statology.org/correlation-between-categorical-variables/ <br />
  https://www.educative.io/blog/one-hot-encoding <br />
  https://www.kaggle.com/code/chrisbss1/cramer-s-v-correlation-matrix/notebook <br />
  https://www.spss-tutorials.com/cramers-v-what-and-why/ <br />
    
ROC and AUC : <br />
  https://www.analyticsvidhya.com/blog/2020/06/auc-roc-curve-machine-learning/#How_Does_the_AUC-ROC_Curve_Work? <br />
  https://www.youtube.com/watch?v=4jRBRDbJemM&ab_channel=StatQuestwithJoshStarmer <br />
  https://www.statology.org/interpret-roc-curve/ <br />
    
Naïve Bayes : <br />
  https://www.sas.com/en_gb/insights/articles/analytics/machine-learning-algorithms.html <br />
  https://github.com/kanchitank/Mushroom-Classification/blob/master/Mushroom-Classification.ipynb <br />
  https://towardsdatascience.com/all-about-naive-bayes-8e13cef044cf <br />
  https://towardsdatascience.com/a-mathematical-explanation-of-naive-bayes-in-5-minutes-44adebcdb5f8 <br />
  https://www.upgrad.com/blog/naive-bayes-classifier/ <br />
  https://www.baeldung.com/cs/naive-bayes-classification-performance <br />

Logistic Regression : <br />
  https://www.datacamp.com/tutorial/understanding-logistic-regression-python <br />
  https://www.kaggle.com/code/enespolat/grid-search-with-logistic-regression <br />
  https://www.analyticsvidhya.com/blog/2021/10/building-an-end-to-end-logistic-regression-model/ <br />
  https://github.com/kanchitank/Mushroom-Classification/blob/master/Mushroom-Classification.ipynb <br />
    
Tuning depth of a Decision Tree : <br />
  https://towardsdatascience.com/understanding-decision-trees-for-classification-python-9663d683c952 <br />
    
Feature Importance : <br />
  https://github.com/kanchitank/Mushroom-Classification/blob/master/Mushroom-Classification.ipynb <br />
  https://towardsdatascience.com/understanding-decision-trees-for-classification-python-9663d683c952 <br />
    
Support Vector Machines : <br />
  https://www.datacamp.com/tutorial/svm-classification-scikit-learn-python <br />
  https://medium.com/@myselfaman12345/c-and-gamma-in-svm-e6cee48626be <br />
    
GridSearchCV : <br />
  https://www.geeksforgeeks.org/svm-hyperparameter-tuning-using-gridsearchcv-ml/ <br />
  https://www.analyticsvidhya.com/blog/2021/06/tune-hyperparameters-with-gridsearchcv/ <br />
  https://vitalflux.com/grid-search-explained-python-sklearn-examples/#:~:text=LogisticRegression%20(Logistic%20regression)%3A%20Grid,most%20appropriate%20value%20of%20C. 

    
    
