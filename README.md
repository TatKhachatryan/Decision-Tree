## Use case
Predict a class of a car using Decision Tree


# What are Decision Trees?
Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression.<br>

Decision tree is a tree shaped diagram used to determinea course of action. Each branch of the tree represents a possible decision, occurence or reaction.<br>

The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.

# How does a decision tree algorithm work?

A decision tree is a structure that includes a root node, branches, and leaf nodes. Each internal node denotes a test on an attribute, each branch denotes the outcome of a test, and each leaf node holds a class label. The topmost node in the tree is the root node.<br>

### Classification and Regression Trees (CART)
Nowadays, Decision Tree algorithm is known by its modern name CART which stands for Classification and Regression Trees. Classification and Regression Trees or CART is a term introduced by Leo Breiman to refer to Decision Tree algorithms that can be used for classification and regression modeling problems. <br>

The CART algorithm provides a foundation for other important algorithms like bagged decision trees, random forest and boosted decision trees. In this kernel, I will solve a classification problem. So, I will refer the algorithm also as Decision Tree Classification problem.

### Attribute selection measures
The primary challenge in the Decision Tree implementation is to identify the attributes which we consider as the root node and each level. This process is known as the attributes selection. There are different attributes selection measure to identify the attribute which can be considered as the root node at each level.<br>


There are 2 popular attribute selection measures.<br>
They are as follows:<br>

* Information gain
* Gini index
