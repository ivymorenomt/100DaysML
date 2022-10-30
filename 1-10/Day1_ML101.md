## DAY 1: Intro to Machine Learning
![ML-screenshot]

Machine Learning is a subset of Artificial Intelligence(AI) in which algorithms learn by example from historical data to predict outcomes and uncover patterns not easily spotted by humans. 

Some of the examples where Machine Learning is being applied to are stock price predictions, self-driving cars, vision processing,  fraudulent insurance claims, recommendation engines, and more! Seems like we are already dependent on machine learning and we are even not aware of it.

To simplify, machine learning algorithms 'learn' by example, and then users apply those self-learning algorithms to uncover insights, relationships and make predictions about the future trend.

The goal of Machine learning is to act more like humans. The smarter they get, the more they help humans accomplish our goals. If implemented effectively, machine learning will allow businesses of different industry sectors uncover optimal solutions to problems, which leads to real, tangible business value.

### Types of Machine Learning
The focus of Machine Learning is to acquire skills or knowledge from experience. It also means, synthesizing useful concepts from historical data.

There are many types of learning that a Machine Learning practitioner may encounter in their experiences. It is about 14 types of learning. In the early writings of this project, I may only cover at least 3 types in the intro, and I might be learning the 11 types left of ML if I see these applicable for the project.

The three types are:
#### 1. Supervised Learning - data that we receive has categories. Example, CSV has labels (data, test) so we would know if a function is wrong.
The algorithm is Y = f(X) where X is the input, and Y is the output.
It is called supervised because the process of an algorithm learning from the training dataset can be thought as a teacher supervising the learning process. Learning stops when the algorithm achieves an acceptable level of performance.

* Classification Learning - this is an apple, this is a pear
* Regression Learning - based on inputs, eg predicting stock prices. Hiring an employee, based on salary,experience, checking if bank transaction is fraudulent or not, etc.

Key Takeaway is that supervised learning will learn on data that is labeled and then it will use these to predict the outcome.

Popular algorithms of Supervised learning are:
* Linear Regression for regression learning
* Random Forest for classification and regression problems.
* Support vector machines for classification problems.

#### 2. Unsupervised Learning - data that we receive has no labels. Example,CSV has no column names.
* Clustering - discover groupings of data, such as grouping customers by purchasing behavior.
* Association - discover rules that describe large portions of data, such as people that buy X also tend to buy Y. Eg Associate what customer might buy in the future.

Some popular algorithms of unsupervised learning are:
* K-Means - for clustering
* Apriori algorithm - association rule problems.
#### 3. Reinforcement Learning - teaching machines thru trial and error/rewards and punishment. It describes a class of problems where an agent operates in an environment and must
It learns a game by simply playing it millions of times until it gets the highest.
It doesn't know what it's doing at first but then it tries to maximize the score and eventually figures out.

Key takeaway is that these types of learning learns from the data that receives and predicts something.

References: 
- [What is Machine Learning][WhatisML-url]
- [14 Types of Machine Learning][14Types-url]
- [Different types of Learning Algorithms][Supervised-Unsupervised-url]


[ML-screenshot]: ../images/ML.png
[WhatisML-url]: https://www.datarobot.com/wiki/machine-learning/
[14Types-url]: https://machinelearningmastery.com/types-of-learning-in-machine-learning/
[Supervised-Unsupervised-url]: https://machinelearningmastery.com/supervised-and-unsupervised-machine-learning-algorithms/