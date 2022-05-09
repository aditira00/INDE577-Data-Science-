
#  Ensemble learning
7 sentences to describe Ensemble learning:

- Predictive model
- Decision Tree determines the predictive value 
- machine learning that seeks better predictive performance by combining the predictions from multiple models
- Each of the feature will have a question that answers in binary form.
- By adding an additional question (feature), we hope to greater define the Yes and No classes
- Decision Trees can also solve quantitative problems as well with the same format
- three main classes of ensemble learning methods are bagging, stacking, and boosting

![image](https://cdn-images-1.medium.com/max/2600/0*PuscwCsUr09xZ0SJ.gif)


Random forest is a machine learning algorithm based on decision trees, which below the a class of machine learning algorithms called `Ensemble methods`. Random trees can handle a mix of categorical and numerical variables, and is less sensitive to scaling and is computationally less intensive than SVM. Random trees also provide an effective way of handling missing data and are less sensitive to overfitting without needing hyperparameter tuning.

# 👩‍💻Algorithm

1. Random J subsets from training data set
2. Build the decision trees using the selected data points (Subsets)
3. Choose the number N for decision trees that you want to build.
4. Repeat Step 1 & 2.
5. After the 4th step for new data points, find the predictions of each decision tree, and assign the new data points to the category that wins the majority votes.


Based on the 👩‍💻Algorithm

![image](https://static.javatpoint.com/tutorial/machine-learning/images/random-forest-algorithm2.png)

## Reference
[towardsdatascience](https://towardsdatascience.com/ensemble-methods-in-machine-learning-what-are-they-and-why-use-them-68ec3f9fef5f)

[javatpoint](https://www.javatpoint.com/machine-learning-random-forest-algorithm)
