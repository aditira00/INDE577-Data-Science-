
# Linear Regression


Linear regression is the process of finding a line that best fits the data points available on the plot, so that we can use it to predict output values for inputs that are not present in the data set we have, with the belief that those outputs would fall on the line.

It is a linear equation that combines a specific set of input values (x) to a predicted output (y). 
![image](https://coolbluedata.com/wp-content/uploads/2021/05/regression3.gif)


LINEAR REGRESSION MODEL:

A simple equation specifies the two variable linear regression model
![image](https://miro.medium.com/max/960/1*jt-pyQQ7bgL2lyganse0nQ.png)

This model consists of two components a systematic part and a random error term.
The systematic component, shows how changes in the independent variable, X, are related to changes in the dependent variable Y.
The nature and magnitude of the connection is given by the regression parameter, b: it indicates how much Y changes for a one unit change in X.
The regression constant, a, is interpreted as the value of Y when X equals 0.

![image](https://research.reading.ac.uk/fiduceo/wp-content/uploads/sites/129/2019/07/wobbling-new-dancing-fig-1.gif)


Forms of linear regession are:

Linear model: a model that assumes a linear relationship between input variables (x) and a single output variable (y), with the goal of calculating y from a linear combination of the input variables (x)

Simple linear regression: When there is a single input variable (x)

Multiple linear regression: When there are multiple input variables

![image](https://datatab.net/assets/tutorial/regression/Linear_Regression.png)


## Error

Whenever we get values based on our X and Y variable, the point may not exactly allign with the linear slope we are trying to get. As we see in the diagram below, the observed Y and pedicted Y is different. A good data scientist or data science enthusiast would try to 
minimize the error to get as many points possible near the linear regression line. 


![image](https://www1.udel.edu/htr/Statistics/Images/Class18/smoking3.gif)


## Evaluation matrix for Regression:



[Documentation](https://linktodocumentation)

R square adn Mean Square error 
For regression problems, we usually use root mean square error (RMSE) and coefficient of determination (R^2) to estimate our linear regression model.

The formula of  is given by ![image](https://miro.medium.com/max/966/1*lqDsPkfXPGen32Uem1PTNg.png)
 
 
 which means :
![image](https://media.geeksforgeeks.org/wp-content/uploads/20200622171741/RMSE1.jpg)

R^2 is the proportion of the variation in the dependent variable that is predictable from the independent variable(s). It's defined as follows
![image](https://www.saedsayad.com/images/MLR_r2.png)


## Mean Squared Error

he Mean Squared Error (MSE) is a measure of how close a fitted line is to data points. For every data point, you take the distance vertically from the point to the corresponding y value on the curve fit (the error), and square the value.
![image](https://miro.medium.com/max/1198/1*BtVajQNj29LkVySEWR_4ww.png)

## Advantages and Disadvantages
Advantages:

Best linear unbiased estimator.
The least square estimator of linear regression model has great properties.
By the Gauss-Markov theorem, the ordinary least squares (OLS) regression produces unbiased estimates that have the smallest variance of all possible linear estimators. This property is called BLUE (Best Linear Unbiased Estimator).

Simple model. The Linear regression model is the simplest equation using which the relationship between the multiple predictor variables and predicted variable can be expressed, and the ordinary least squares error function is also very simple and straight-forward.

Computationally friendly. The modeling speed of linear regression is fast as it does not require complicated calculations and runs predictions fast when the amount of data is large.

Great interpretability of the output. The ability of linear regression to determine the relative influence of one or more predictor variables to the predicted value when the predictors are independent of each other is one of the key reasons of the popularity of linear regression. The model derived using this method can express the what change in the predictor variable causes what change in the predicted or target variable.

Disadvantages:
Overly-Simplistic. 
The linear regression model is too simplistic to capture real world complexity.
The linear regression assumes a linear relationship between independent variables and dependent variable, which cannot represent more complex relationships in real world.

Independence of variables. Assumes that the predictor variables are not correlated which is rarely true. It is important to, therefore, remove multicollinearity (using dimensionality reduction techniques) because the technique assumes that there is no relationship among independent variables. In cases of high multicollinearity, two features that have high correlation will influence each other’s weight and result in an unreliable model.



## References By 
 - [Regression](https://www1.udel.edu/htr/Statistics/Notes/class18.html)
 - [Linear Regression](https://github.com/Madison-Bunting/INDE-577/tree/main/supervised%20learning/0%20-%20linear%20regression)


