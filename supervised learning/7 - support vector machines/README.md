
# Support Vector Machines 

 Support Vector Machines are machine learning algorithms that are used for classification and regression purposes. SVMs are one of the powerful machine learning algorithms for classification, regression and outlier detection purposes. An SVM classifier builds a model that assigns new data points to one of the given categories. Thus, it can be viewed as a non-probabilistic binary linear classifier.


![Image](https://vatsalparsaniya.github.io/ML_Knowledge/_images/gif.gif)



We can use them to classify basically anything from cats and dogs to strawberries and apples using Linear SVM, this algorithm separates the data with a straight line.

## Common terminologyies:


A hyperplane is a decision boundary that differentiates the two classes in SVM. A data point falling on either side of the hyperplane can be attributed to different classes. The dimension of the hyperplane depends on the number of input features in the dataset.

![image](https://miro.medium.com/max/1280/1*H2QEWsP9-W4rBdIaxfVExg.jpeg)

There are two types of Margin:

Soft Margin:
![image](https://media.cheggcdn.com/media%2F41c%2F41c5b301-57d7-4056-a959-a4660ba8a205%2Fphp10KXpi.png)

Hard Margin, aka Hyperplane: 
A hyperplane is a decision boundary that differentiates the two classes in SVM. A data point falling on either side of the hyperplane can be attributed to different classes. The dimension of the hyperplane depends on the number of input features in the dataset.

![image](https://miro.medium.com/max/1280/1*H2QEWsP9-W4rBdIaxfVExg.jpeg)

- Support Vectors:
Support vectors are datapoints closer to the hyperplate that influence the position and orientation of the hyperplane - we can use these support vectors to maximize the margin of the classifier. Deleting them changes the position of the hyperplane.
Using Update weight function in step 1:

Step 1 :

![image](https://camo.githubusercontent.com/df04a86757fa420b391ad69ea49a9ad973662d73d7938b0e21f217ce2a04f58b/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313035302f312a5755706874594c66544f416f6158515876496d4265412e706e67)
Step 2 :
![image](https://camo.githubusercontent.com/ffb4b9ebed11194fba575806298a4e1d2b8f0c375c3d0e11be9a4dd2717c893e/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f3436322f312a2d6e4b455872576f73384975662d445753765f7372512e706e67)

Step 3 :
![image](https://camo.githubusercontent.com/c14ead46c4a8a1b0e869d9bffea7e20e0f566872f50b10c66f81a5eac1b8707e/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f3634322f312a746e764d68414b615455434f343364694576745441512e706e67)


Step 4:
![image](https://camo.githubusercontent.com/7680e45995a33b8f8e5c848ab0277c21500b204a7eebad47d56ca57d5625d661/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313632342f312a68486c79746a566b3664374f325757764732476469672e706e67)

Step 5:
![image](https://camo.githubusercontent.com/8ecbb51f79ed4451fae473fba4d9a6ce69f8662019071845e360d99bf7e2a6a5/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313430302f312a475141643238624b384c4b4f4c326b4f4f46592d74672e706e67)


- Kernel trick:

The “trick” is that kernel methods represent the data only through a set of pairwise similarity comparisons between the original data observations x (with the original coordinates in the lower dimensional space), instead of explicitly applying the transformations ϕ(x) and representing the data by these transformed coordinates in the higher dimensional feature space.

In 1-dimension, this data is not linearly separable, but after applying the transformation ϕ(x) = x² and adding this second dimension to our feature space, the classes become linearly separable.
## Reference


[Github](https://gist.github.com/pb111/ca4680d8960c46aeb1b824a93a079fa7)

[towardsdatascience](https://towardsdatascience.com/i-support-vector-machines-and-so-should-you-7af122b6748)
