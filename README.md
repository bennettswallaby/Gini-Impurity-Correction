# Gini-Impurity-Correction
Calculated, Gini Impurity by subtracting the sum of the squared probabilities of each class via machine learning.

Decision trees are one of the most used machine learning models because of their ease of implementation and simple interpretations. To better learn from the data they are applied to, the nodes of the decision trees need to be split based on the attributes of the data. In this article, we will understand the need of splitting a decision tree along with the methods used to split the tree nodes. Gini impurity, information gain and chi-square are the three most used methods for splitting the decision trees. Here we will discuss these three methods and will try to find out their importance in specific cases. The major points that we will cover in this article are outlined below.  

![terminologies](https://user-images.githubusercontent.com/118565420/202835656-9609d3e4-dc08-4fa9-a99a-8005ff9505e7.png)

Node Splitting in Decision Trees

Decision trees are totally dependent on the objective variable, although their algorithms differ from those used for classification and regression trees. There are numerous approaches for deciding how to partition the provided data. 

The primary purpose of decision trees is to find the best splits between nodes that will best divide the data into the appropriate categories. To accomplish this, we must employ the proper decision-making procedures. The rules have a direct impact on the algorithm’s performance.

There are a few assumptions that must be made:

The entire data set is considered the root at first, and then we utilize methods to break or divide the root into subtrees.
The feature values are classified as categorical. If the values are continuous, they are split before the model is built.
Recursively, records are distributed based on attribute values.
A statistical approach is used to order characteristics as the tree’s root or an internal node.
Decision Tree Splitting Methods
It’s tough to decide which variables to put at the root or at different levels of the tree as internal nodes when the dataset comprises N variables. Choosing any node as the root at random will not solve the problem. We can receive disappointing results with limited precision if we use a random technique. Researchers collaborated to develop answers to the attribute selection challenge. They recommended employing criteria such;

Gini Impurity

Information Gain
Chi-Square
Each attribute’s value will be calculated using these criteria. The values are sorted, and characteristics are ordered in the tree, with the attribute having the highest value (in the case of information gain) at the top. We assume categorical attributes for Information Gain and continuous attributes for the Gini impurity. 

Gini Impurity
The division is called pure if all elements are accurately separated into different classes (an ideal scenario). The Gini impurity (pronounced “genie”) is used to predict the likelihood that a randomly selected example would be incorrectly classified by a specific node. It is called an “impurity” metric because it shows how the model differs from a pure division.

The degree of Gini impurity ranges from 0 to 1, with 0 indicating that all of the elements belong to a single class and 1 indicates that only one class exists. The Gini impurity of value 1 indicates that all of the items are randomly distributed over various classes, whereas a value of 0.5 indicates that the elements are uniformly distributed across some classes. It is stated as given below formula originally by Leo Breiman in 1984.

Information Gain = 1 – Entropy

- I hope this information helps you. 
- Thanks and Regards
- Divyansh Palia

