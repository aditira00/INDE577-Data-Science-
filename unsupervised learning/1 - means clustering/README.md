
# Unsupervised Machine Learning
Unsupervised learning is very similar to how a baby 👶 tries to understand things. Human learns to think by their own experiences, which makes it closer to the real AI. 

Unsupervised learning works on unlabeled and uncategorized data which make unsupervised learning more important.

![Image](https://miro.medium.com/max/1280/1*HU617gljScDVnanadMzCcQ.gif)

# K means clustering
Clustering is a set of techniques used to classify data into groups, colonies or clusters.

 Clusters are loosely defined as clusters of data objects that are more similar to other objects in their cluster than they are to data objects in other clusters. 



![image](https://miro.medium.com/max/1400/1*qdAW1TjCN57h1lbuuzvchg.gif)



# 👩‍💻Algorithm 

We dont have a target variable/ score, we are going to take random centroids.

 In this algorithm, we have to specify the number of clusters (which is a hyperparameter) we want the data to be grouped into.  
1. Choose a number of clusters “K”
2. Randomly assign each point to Cluster.
    Until cluster stop changing, repeat the following
3. For each cluster, compute the centroid of the cluster by taking the mean vector of the points in the cluster.
4. Assign each data point to the cluster for which the centroid is closest


## Three common ways of selecting the number of clusters "k"

 - Elbow method 

Elbow method is one of the most popular method used to select the optimal number of clusters by fitting the model with a range of values for K in K-means algorithm. Elbow method requires drawing a line plot between SSE (Sum of Squared errors) vs number of clusters and finding the point representing the “elbow point” (the point after which the SSE or inertia starts decreasing in a linear fashion). Here is the sample elbow point. In the later sections, it is illustrated as to how to draw the line plot and find elbow point. 


![Image](https://editor.analyticsvidhya.com/uploads/62725cluster0.PNG)


 - Silhouette coefficient

 ![Image](https://editor.analyticsvidhya.com/uploads/45590cluster1.PNG)


 S(i) is the silhouette coefficient of the data point i.
a(i) is the average distance between i and all the other data points in the cluster to which i belongs.
b(i) is the average distance from i to all clusters to which i does not belong.

 ![image](https://editor.analyticsvidhya.com/uploads/90733cluster2.PNG)

![image](https://editor.analyticsvidhya.com/uploads/56608cluster3.PNG)


## Compute the centroid by calculating distance from each feature vector to each centroid 

 -  Eucledean Distance
![image](https://www.gstatic.com/education/formulas2/443397389/en/euclidean_distance.svg)

 - Manhattan distance 


![image](https://cdn-images-1.medium.com/max/800/1*-xXnL0liqSl-flWgCTFbiw.png)




## Reference

- [realpython](https://realpython.com/k-means-clustering-python/)

- [K means Clustering](https://datascienceplus.com/k-means-clustering/#:~:text=Finding%20a%20K%2Dvalue&text=First%20of%20all%20compute%20the,as%20disortation%20will%20be%20small.)

- [vitalflux](https://vitalflux.com/k-means-elbow-point-method-sse-inertia-plot-python/#:~:text=Elbow%20method%20is%20used%20to,errors%20vs%20number%20of%20clusters.)

- [analyticsvidhya](https://www.analyticsvidhya.com/blog/2021/05/k-mean-getting-the-optimal-number-of-clusters)

- [RandyRDavila](https://youtu.be/hBnGg74qn5c)

