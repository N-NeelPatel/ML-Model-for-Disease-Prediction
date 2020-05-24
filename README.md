# ML-Model-for-Disease-Prediction
# Content
1. [Introduction](#Introduction)
2. [How to run](#How-to-run)
3. [Features](#Features)

# Introduction
ML model for diseases prediction is a GUI based application which helps in predicting the diseases, from provided symptoms. It will use various algorithms for prediction.
# How to run
While there is no executable available, so you can try **ML Model for disease Prediction** with source code.
Steps to run:
1. Clone this Repo
2. Run with command python main.py.
# Features
![Main Screen](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/gui1.PNG)
Above is the screenshot of the project.
Now, we will see each section one by one,
## Symptom Section
In this section five fields are given to choose various symptoms. 
### Example: 
###
![Symptom Section](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/gui-symptoms.PNG)
## Algorithm Section
### Example of GUI: 
![algo section](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/gui-algo.PNG)
###
In this section three buttons are used to select the algorithm to be used in the prediction. Here, three different algorithms are used in order to have maximum accuracy and to make a judgement from prediction.
### 1. Decision Tree
![decisiontree](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/decision.gif)
#### Introduction
Classification is a two-step process, learning step and prediction step, in machine learning. In the learning step, the model is developed based on given training data. In the prediction step, the model is used to predict the response for given data. Decision Tree is one of the easiest and popular classification algorithms to understand and interpret.
#### Decision Tree Algorithm
Decision Tree algorithm belongs to the family of supervised learning algorithms. Unlike other supervised learning algorithms, the decision tree algorithm can be used for solving regression and classification problems too. The goal of using a Decision Tree is to create a training model that can use to predict the class or value of the target variable by learning simple decision rules inferred from prior data(training data). In Decision Trees, for predicting a class label for a record we start from the root of the tree. We compare the values of the root attribute with the record’s attribute. On the basis of comparison, we follow the branch corresponding to that value and jump to the next node.
#### Types of Decision Trees
Types of decision trees are based on the type of target variable we have. It can be of two types:
1. **Categorical Variable Decision Tree:** Decision Tree which has a categorical target variable then it called a Categorical variable decision tree.
2. **Continuous Variable Decision Tree:** Decision Tree has a continuous target variable then it is called Continuous Variable Decision Tree.
**Example:-** Let’s say we have a problem to predict whether a customer will pay his renewal premium with an insurance company (yes/ no). Here we know that the income of customers is a significant variable but the insurance company does not have income details for all customers. Now, as we know this is an important variable, then we can build a decision tree to predict customer income based on occupation, product, and various other variables. In this case, we are predicting values for the continuous variables.

To know more about decision tree algorithm and how it works, visit **[decision tree](https://dataaspirant.com/2017/01/30/how-decision-tree-algorithm-works/)** page.
### 2. Random Forest
![RandomForest](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/random.jpeg)
#### Introduction
A big part of machine learning is classification — we want to know what class (a.k.a. group) an observation belongs to. The ability to precisely classify observations is extremely valuable for various business applications like predicting whether a particular user will buy a product or forecasting whether a given loan will default or not.
#### Random Forest Classifier
Random forest, like its name implies, consists of a large number of individual decision trees that operate as an ensemble. Each individual tree in the random forest spits out a class prediction and the class with the most votes becomes our model’s prediction (see figure below).
####
![randomforest](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/random2.jpeg)
####
The fundamental concept behind random forest is a simple but powerful one — the wisdom of crowds. In data science speak, the reason that the random forest model works so well is: **A large number of relatively uncorrelated models (trees) operating as a committee will outperform any of the individual constituent models.**
The low correlation between models is the key. Just like how investments with low correlations (like stocks and bonds) come together to form a portfolio that is greater than the sum of its parts, uncorrelated models can produce ensemble predictions that are more accurate than any of the individual predictions. **The reason for this wonderful effect is that the trees protect each other from their individual errors** (as long as they don’t constantly all err in the same direction). While some trees may be wrong, many other trees will be right, so as a group the trees are able to move in the correct direction. So the prerequisites for random forest to perform well are:
1. There needs to be some actual signal in our features so that models built using those features do better than random guessing
2. The predictions (and therefore the errors) made by the individual trees need to have low correlations with each other.
To know more about Random Forest algorithm and how it works, visit **[Random Forest](https://towardsdatascience.com/understanding-random-forest-58381e0602d2)** page.
### 3. Naive Bayes
![Naive Bayes](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/naive.jpeg)
#### Principle of Naive Bayes Classifier
A Naive Bayes classifier is a probabilistic machine learning model that’s used for classification task. The crux of the classifier is based on the Bayes theorem.
#### Bayes Theorem
![formula](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/bayes.png)
####
Using Bayes theorem, we can find the probability of A happening, given that B has occurred. Here, B is the evidence and A is the hypothesis. The assumption made here is that the predictors/features are independent. That is presence of one particular feature does not affect the other. Hence it is called naive.
#### Conclusion
Naive Bayes algorithms are mostly used in sentiment analysis, spam filtering, recommendation systems etc. They are fast and easy to implement but their biggest disadvantage is that the requirement of predictors to be independent. In most of the real life cases, the predictors are dependent, this hinders the performance of the classifier.
To know more about Naive Bayes algorithm and how it works, visit **[Naive Bayes](https://towardsdatascience.com/naive-bayes-classifier-81d512f50a7c)** page.




## Predicted Results
This section will show the results from above section. It will show the predicted outcome from using above given algorithms.
###
![predicted-outcome](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/gui-result.PNG)
# Example
![example](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/gui-2.PNG)

