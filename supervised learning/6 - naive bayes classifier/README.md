
# Naive Bayes Classifier 
Naive Bayes methods are a set of supervised learning algorithms based on applying Bayes’ theorem with the “naive” assumption of conditional independence between every pair of features given the value of the class variable. 
![image](https://cdn-images-1.medium.com/max/600/1*aFhOj7TdBIZir4keHMgHOw.png)



Naive Bayes classifier is a collection of many algorithms where all the algorithms share one common principle, and that is each feature being classified is not related to any other feature. The presence or absence of a feature does not affect the presence or absence of the other feature.


## Three main types of classifiers 

 ![image](https://miro.medium.com/max/1336/1*-ILVYuyxT3ypZ9CF0BEgWQ.png)


| Gaussian Naive Bayes |

Gaussian Naive Bayes supports continuous valued features and models each as conforming to a Gaussian (normal) distribution. 
One only need to estimate the mean and the standard deviation from your training data.



| Bernoulli Naive Bayes |

 Bernoulli Naive Bayes is used for discrete data, where features are only in binary form, eg: 1 and 0, bad or good, married or single, sun or moon.

 ![image](https://iq.opengenus.org/content/images/2020/05/11-1.jpg)

 let's consider 'p' as probability of success and 'q' as probability of failure and q=1-p
For a random variable 'X' in Bernoulli distribution. 

| Multinomial Naive Bayes |

Multinomial Naive Bayes uses multinomimal distribution and is used when features represent frequency of something occurring, like the number of words in a letter or essay classification purposes


