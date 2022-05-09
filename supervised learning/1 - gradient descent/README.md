
# Gradient Descent 


Gradient descent is an optimization algorithm to find a local minimum of a differentiable function. It is most often used to find coefficient values that minimize a cost function.

Imagine you are walking down a mountain or a valley and this is its topographical map (where lines that are closer together indicate the slope of the valley is steeper between them just like a "V".).

 In the case below, the valley gets less steep the lower you decline, meaning the reduced gradient correlates with a reduced slope and step size for the person.

![image](https://suniljangirblog.files.wordpress.com/2018/12/1-1.gif?w=379)

Ever heard of using training models to train a data set? 
Behind the scenes its gradient descent  Algorithm that trains it.


 ![image](https://miro.medium.com/max/604/1*MpLkcugbeMrJvFlz69LTNQ.jpeg)



Gradient Descent is an optimizing algorithm used in Machine/ Deep Learning algorithms. The goal of Gradient Descent is to minimize the objective convex function f(x) using iteration.

Gradient Descent is widely used in Industrial Engineering. Especially in operations research, where one has to minimize cost of transportation, inventory, fixed cost, distances between plants, etc.


# Algorithm 

![image](https://editor.analyticsvidhya.com/uploads/90857Screenshot%20(41)_LI.jpg)


![image](https://editor.analyticsvidhya.com/uploads/36152Screenshot%20(43).png)

# Learning Rate 
The function initializes at a given point, then iteratively takes steps in the direction of steepest descent. The size of the steps is called the learning rate, larger learning rates can cause the algorithm to skip around and potentially miss the local minimum (as seen below), while small learning rates follow the curve of the function.

![image](https://miro.medium.com/max/1400/0*oqzNRIFF5k75j33G.png)

Big learning rate :
As seen in the image aboove the bigger learning rate jumps from one side of the curve to another and as it goes in the end it just keeps bouncing because it keeps taking larger steps. 

Large learning rates puts the model at risk of overshooting the minima so it will not be able to converge: what is known as exploding gradient.

Small Learning rate:
The learning rate controls how quickly the model is adapted to the problem. Smaller learning rates require more training epochs given the smaller changes made to the weights each update, whereas larger learning rates result in rapid changes and require fewer training epochs.
However, it takes significantly longer to train.


## Types of Gradient Descent Algorithms

Various variants of gradient descent are defined on the basis of how we use the data to calculate derivative of cost function in gradient descent. Depending upon the amount of data used, the time complexity and accuracy of the algorithms differs with each other.

Gradient Descent can further be studied from the following:

[Batch Gradient Descent](https://towardsdatascience.com/batch-mini-batch-stochastic-gradient-descent-7a62ecba642a)

[Stochastic Gradient Descent](https://towardsdatascience.com/batch-mini-batch-stochastic-gradient-descent-7a62ecba642a)

[Mini-Batch Gradient Descent](https://towardsdatascience.com/batch-mini-batch-stochastic-gradient-descent-7a62ecba642a)




Resources from :
[towardsdatascience](https://towardsdatascience.com/batch-mini-batch-stochastic-gradient-descent-7a62ecba642a)