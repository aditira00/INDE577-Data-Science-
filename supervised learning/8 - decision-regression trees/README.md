
# Decision Regression Tree

 🧔 Darwin's theory: “survival of the fittest” states that the one who evolve and fitter than other species servive. But werent we studying Decision Tree ?

Yes! Lets take humans in Titanic; the women and children were the first to let off when the ship started sinking. This is a decision which effects the survival rate. This decision for females and under 15 humans grants them a higher chance of survival than Males.  

![image](https://media3.giphy.com/media/3orif0iFlJKUTgNYD6/200.gif)


![image](https://annalyzin.files.wordpress.com/2016/07/decision-trees-example-multiple-categories-tutorial2.png)


In a Decision tree, there are two nodes, which are the Decision Node and Leaf Node. Decision nodes are used to make any decision and have multiple branches, whereas Leaf nodes are the output of those decisions and do not contain any further branches.

Decision Tree always have questions which answer in Binary: Like Yes and No or 1 and 0.


👩‍💻Algorithm:

Step-1: Begin the tree with the root node, says S, which contains the complete dataset.

Step-2: (Cleaning the data) Find the best attribute in the dataset using Attribute Selection Measure (ASM).

Step-3: Divide the S into subsets that contains possible values for the best attributes.

Step-4: Generate the decision tree node, which contains the best attribute.

Step-5: Recursively make new decision trees using the subsets of the dataset created in step -3. Continue this process until a stage is reached where you cannot further classify the nodes and called the final node as a leaf node.

1. Information Gain:

Information gain is the measurement of changes in entropy after the segmentation of a dataset based on an attribute.
It calculates how much information a feature provides us about a class.
According to the value of information gain, we split the node and build the decision tree.

A decision tree algorithm always tries to maximize the value of information gain, and a node/attribute having the highest information gain is split first.
 It can be calculated using the below formula:
Information Gain= Entropy(S)- [(Weighted Avg) *Entropy(each feature)  


2. Gini Index:
Gini index is a measure of impurity or purity used while creating a decision tree in the CART(Classification and Regression Tree) algorithm.
An attribute with the low Gini index should be preferred as compared to the high Gini index.

Gini index can be calculated using the below formula:

Gini Index= 1- ∑jPj2

Pruning:

Pruning is a process of deleting the unnecessary nodes from a tree in order to get the optimal decision tree.

A too-large tree increases the risk of overfitting (forcefully trying to fit into a class), and a small tree may not capture all the important features of the dataset. Therefore, a technique that decreases the size of the learning tree without reducing accuracy is known as Pruning.



## Reference

[javatpoint](https://www.javatpoint.com/machine-learning-decision-tree-classification-algorithm)

