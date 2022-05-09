# K Nearest Neighbors (KNN)

K Nearest Neighbors is a simple algorithm that stores all the data or classifies them based on a similarity measure.

Suppose a child of age 5 is given Pears, Strawberries and Apples. He will automatically start segrating them without even knowing their names, each strawberry is of different size, pears might be green and yellow and apples might or might not have the exact same redness. 
Still, a child might be able to segregate it based on hardness, Apples might seem too hard than strawberry. The pear might have a very distinct smell and is not as red or pink in colour as strawberry and pears.

Now imagine you are being blindfolded and given the same fruits, your brain starts giving points to the fruits based on softness, texture of the berries and size. 
Similar to those points, based on the points, weights we can classify different objects, animals and colors.


![image](https://static.javatpoint.com/tutorial/machine-learning/images/clustering-in-machine-learning.png)


 It is mostly used to classify a datapoint based on how its neighbors are classified. This method is used in areas from recommendation systems to anomaly detection to image/text classification. KNN can also be used for regression, though this application is less common than classification.

Classification in short is, KNN essentially boils down to forming a majority vote between K most similar (i.e. closest) instances to a given "unseen" observation.

![image](https://miro.medium.com/max/1400/1*b2sO2f--yfZiJazc5rYSpg.gif)


## Unsupervised Learning in K 


We dont have a target variable/ score, we are going to take random centroids.

 In this algorithm, we have to specify the number of clusters (which is a hyperparameter) we want the data to be grouped into.  
1. Choose a number of clusters “K”
2. Randomly assign each point to Cluster.
    Until cluster stop changing, repeat the following
3. For each cluster, compute the centroid of the cluster by taking the mean vector of the points in the cluster.
4. Assign each data point to the cluster for which the centroid is closest


## Reference
[K means Clustering](https://datascienceplus.com/k-means-clustering/#:~:text=Finding%20a%20K%2Dvalue&text=First%20of%20all%20compute%20the,as%20disortation%20will%20be%20small.)

[vitalflux](https://vitalflux.com/k-means-elbow-point-method-sse-inertia-plot-python/#:~:text=Elbow%20method%20is%20used%20to,errors%20vs%20number%20of%20clusters.)

[analyticsvidhya](https://www.analyticsvidhya.com/blog/2021/05/k-mean-getting-the-optimal-number-of-clusters)

[RandyRDavila](https://youtu.be/hBnGg74qn5c)