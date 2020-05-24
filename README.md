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


## Predicted Results
This section will show the results from above section. It will show the predicted outcome from using above given algorithms.
![predicted-outcome](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/gui-result.PNG)
# Example
![example](https://github.com/N-NeelPatel/ML-Model-for-Disease-Prediction/blob/master/imgs/gui-2.PNG)

