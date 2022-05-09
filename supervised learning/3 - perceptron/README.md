
# PERCEPTRON

A Perceptron is an algorithm for supervised learning of binary classifiers. The algorithm is inspired by the way neurons work together in the brain, the perceptron is a single-layer neural network.

Each neuron takes inputs, weighs them separately, sums them up and passes this sum through a nonlinear function to produce output.
Numerous amount of inputs are separately weighted. Every neuron is connected to another neuron via connection link.


![image](https://thumbs.gfycat.com/InfamousOfficialBlackbird-max-1mb.gif)



## Algorithm 👩‍💻

Linear classifier: training data should be classified into corresponding categories (i.e. if there are two categories, all the training data must lie in those two categories)

Binary classifier: defines that there should only be two categories(( 1 and 0) or(-1 and 1) etc)



There are three phases to achieve perceptron (single neuron network )
However I am going to use five to elaborate on those three phases in coding.
Phase 1
1. Data Processing

As a binary classifier, perceptrons are meant to classify input into two groups: yes/no, gas/diesel , sun/moon, etc, corresponding to 1/0 or 1/-1 outputs (depending on the selected activation function). To prepare data, we must first determine the two output groups and classify data in numerical terms, at which point the data will be in a format that will allow the perceptron to be trained.



2. Classification of X and Y constriants 

Here, X is defined as identifying whether the car uses gas or diesel fuel type. 
    Through "compressionratio" and "horsepower" which is our Y here.



3. Activation Functions
Choosing the Activation Functions
The activation function is how the input data will be interpreted. The activation function associated with the perceptron is the sign activation function, which classifies any output less than 0 as -1, and any output greater than or equal to 0 as 1. This is very similar to the binary step activation function.

4. Weights 

!
![image](https://pabloinsente.github.io/assets/post-6/linear-function-adaline.png)

The output can be represented as “1” or “0.”  It can also be represented as “1” or “-1” depending on which activation function is used.

5. Update Weights 

By iterating through the algorithm, the separation line moves in space and after a few epochs (which in our case is 1000), the algorithm classifies it correctly.

In the Perceptron learnning rule, predicted output is compared with known output; if they do not match, error is propagated backward to allow weight adjustment to happen.


