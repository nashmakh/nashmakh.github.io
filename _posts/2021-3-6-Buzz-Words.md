---
layout: post
title: Data Science Buzzwords Demystified 
---

Buzz words like Machine Learning, Deep Learning, Supervised learning, Unsupervised learning, Neural Networks are thrown around a lot these days. But what do they really mean? This blog post will hopefully demystify these terms for you and encourage you to dive deeper into these topics.

## Machine Learning

Machine learning can be defined as the use of algorithms to learn from data and make predictions about something in the world. So instead of writing code to solve a particular problem every time, there is automation in the sense that the machine is “trained” using large amount of data that give it the ability to perform a task. We will see what it means to train a model later in this article.

## Supervised Learning

Now that we have a general idea about Machine learning, let look at what it means to create a supervised learning model.

In supervised learning, you train the machine using data that is labelled. That is, you pass through data that is already identified with the correct answer. The machine learns from these examples and uses these learnings to match similarities in unseen data to predict a response. 

Within Supervised learning, there are 2 branches based on the output we desire, Classification and Regression. 

**Classification** is when we want the algorithm to classify data. For example, we provide the machine with labeled pictures of many different kinds of apples and cupcakes. It learns from the properties in these picture - shape of a cupcake, stem of an apple, etc to correctly classify an unseen, unlabelled picture of a cupcake (Figure 1).

 ![supervised.png](attachment:ef7e2e3f-4c44-4ff7-a741-9665eb3c5b82.png)
 
Figure 1. Supervised learning – Classification

  **Regression** (Figure 2) is used when we want to obtain a value, usually continuous. For example, we provide the machine with housing data that shows the price of the house based on various factors like size of unit, age of unit, etc. The machine then uses a regression model to predict housing prices using factor values not seen in the data set.


 ![supervised1.png](attachment:66ea4a0a-f145-4c7f-aeb7-435305c03302.png)
 
Figure 2. Supervised learning - Regression

Some other real-world examples built on classification and regression models are spam email classification and stock price prediction, respectively.

## Unsupervised learning

You may have guessed by now – Unsupervised learning is indeed when you train a machine with data that is unlabelled. That is, you only have input data and no corresponding values to classify the data. 

In unsupervised learning, the algorithm works out and presents interesting structure in the data on its own. The goal is to group data with underlying similarities in order to learn more about these groups. In practice, unsupervised learning is highly useful as lot of time labelled data is difficult or expensive to obtain, as someone would have had to go through all the training data and label it. 

As with supervised learning, unsupervised learning also has two branches – clustering and association.

**Clustering** deals with finding patterns in data and grouping natural clusters (groups) if they exist in the data. There are certain modifications that can be made to control the granularity of these groups. In Figure 3 below, an unsupervised learning algorithm called K-means Clustering finds 3 distinct clusters in the data.

 ![unsupervised.png](attachment:86b97249-3a40-4335-98bc-bf4f71295676.png)
 
Figure 3. Unsupervised learning - K-means Clustering algorithm in action

**Association** deals with discovering correlations between data objects in large databases, such as people who buy X are also likely to buy Y.

## Neural Networks

Another buzz word you were probably eager to learn about is Neural Networks. Neural Networks is a particular type of supervised learning model that can be used for classification or regression. An illustration of how a neural network model works in shown in Figure 4.

 ![neural network.png](attachment:b28a233b-49bf-4337-a0d4-480a9128fec2.png)
 
Figure 4. A neural network structure example

The inputs are broken down into these middle layers called “hidden layers” where they are evaluated in order to obtain the output. When there are more than 1 hidden layers like in Figure 4, this is said to be a deep network, therefore the above neural network model is a **Deep Learning** model. 

## Summary

Machine learning, very broadly, is the training of a model to solve problems. Supervised and Unsupervised learning are 2 branches of Machine learning. Supervised learning uses label data to train models, while unsupervised learning by definition uses data that is unlabeled to train models. Both Supervised and Unsupervised learning have 2 branches. Classification and Regression under Supervised learning & Clustering and Association under Unsupervised learning. Neural network is a type of Supervised learning model, and if a neural network has more than one hidden layer it is considered a Deep learning model.

### Reference

Figure 1 - https://medium.com/@canburaktumer/machine-learning-basics-with-examples-part-2-supervised-learning-e2b740ff014c

Figure 2 - https://www.gatevidyalay.com/category/subjects/machine-learning/

Figure 3 - https://www.iotforall.com/machine-learning-crash-course-unsupervised-learning

Figure 4 - https://www.kdnuggets.com/2019/11/designing-neural-networks.html

Inspired by the following blogs:

https://machinelearningmastery.com/supervised-and-unsupervised-machine-learning-algorithms/

https://www.guru99.com/supervised-vs-unsupervised-learning.html

https://www.iotforall.com/machine-learning-crash-course-unsupervised-learning

https://www.educba.com/supervised-learning-vs-unsupervised-learning/