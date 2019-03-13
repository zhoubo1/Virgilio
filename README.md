# Machine-Learning Study-Path
## A complete ML study path, centered around TensorFlow and Scikit-Learn

This repository is intended to provide a complete and organic learning path to getting started with Machine Learning.
You will understand both theory and be able to apply it in practice, with hands-on project.

It does not require any previous knowledge, but being confident with programming and high school math is necessary to understand and implement Machine Learning concepts.

I **strongly recommend** to buy [**this**](https://www.amazon.it/Hands-Machine-Learning-Scikit-Learn-Tensorflow/dp/1491962291/ref=pd_sbs_14_1/260-9599700-1757805?_encoding=UTF8&pd_rd_i=1491962291&pd_rd_r=23993915-4513-11e9-ad92-43c54a5a8a65&pd_rd_w=QNr5b&pd_rd_wg=Si7Nj&pf_rd_p=37660d27-94f1-4ebe-be01-184b332a9b15&pf_rd_r=SF0KMBGABMY3T790JY7Z&psc=1&refRID=SF0KMBGABMY3T790JY7Z) phenomenal book: "Hands-On Machine Learning with Scikit-Learn and TensorFlow" by  OreillY, which inspired me and has driven most of the organization and hierarchy of the content listed above.

A part from this, **every content** listed here is open source and free, most of that coming from the world-renowned universities and open source associations. 


#### I organized the Path in 4 sections:

#### Prerequisites
- Python
- The Math you need
- The Machine Learning landscape

#### Machine learning with Scikit-Learn
- Why Scikit-Learn?
- End-to-End Machine Learning project 
- Linear Regression 
- Classification
- Training models
- Support Vector Machines
- Decision Trees
- Ensemble Learning and Random Forest 

#### Neural Networks with TensorFlow
- Why TensorFlow?
- Up and Running with TensorFlow
- ANN - Artificial Neural Networks 
- CNN - Convolutional Neural Networks
- RNN - Recurrent Neural Networks
- Training Networks: Best practices 
- AutoEncoders
- Reinforcement Learning

#### Utilities
- Machine Learning Projects 
- Data Science Tools
- Blogs / Youtube Channels / Websites worth taking a look!


So let's get started!

---------------------------------------------------------------

## Prerequisites

### Python

According to Sun Tzu:
> If you don't know Python, learn it yesterday!

Python is one of the most used and loved programming languages, and it's necessary to get things done in the Machine Learning field. Like most of the frameworks of the bigger Data Science field, TensorFlow is married with Python and Scikit-Learn is written in Python.  

If you don't know the basics, just start from [here](https://pythonprogramming.net/introduction-learn-python-3-tutorials/).\
Else if you know the syntax and you want to have a more solid Python background (recommended) take this Intermediate Python Course from [here](https://pythonprogramming.net/introduction-intermediate-python-tutorial/).\
If you are looking for tons of exercises to get your hands dirty and get experience with Python, check [here](https://www.w3resource.com/python-exercises/) and [here](https://www.practicepython.org/).

Once you're familiar with Python, take a look at [Numpy](https://docs.scipy.org/doc/numpy-1.13.0/user/whatisnumpy.html), an important module for math operations, that allows you to import in Python the [Tensor](https://www.kdnuggets.com/2018/05/wtf-tensor.html) data type, which is the most used in ML (especially when dealing with Neural Nets).
[It's not a matrix!](https://medium.com/@quantumsteinke/whats-the-difference-between-a-matrix-and-a-tensor-4505fbdc576c)

### The math you need

Who tells that the math behind Machine Learning is hard... it's not so wrong! But you have to consider that every time you're going to use it, it will be handled by the machine for you! So, the important is to grasp the main concepts and recognize limits and applications of those. No one is going to ask you to calculate a gradient by hand! So, if you are not familiar with these concepts, check them, because they are the reason behind everything.

With these three resources, you'll get out the most of what you really need to understand things deeply.

A top course about linear algebra is [here](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/).\
Integrate with basic probabilities and statistic concepts [here](https://www.edx.org/course/introduction-to-probability-0).\
The most of the remaining math you need [here](https://explained.ai/matrix-calculus/index.html#sec4.5).


### The machine learning Landscape

Directly from the book cited earlier, this is the most concise and illuminating overview of **what is** and **when you need** machine learning. Let's stop use buzzwords!
Check it [here](https://www.oreilly.com/library/view/hands-on-machine-learning/9781491962282/ch01.html).

----------------------------------------------------------------

## Machine Learning with Scikit-Learn

When we learn something new, especially if wide and complex, is necessary to avoid confusion, so 
I tried to create the next steps of the path preferring contents from the same context and authors, when possible.
When not possible, I collected both theory and examples, further some pointers to resources like "best practices for _______".


### Why Scikit-Learn

[Scikit-Learn](https://scikit-learn.org/stable/) one of the most complete, mature and well-documented library for Machine Learning tasks. It comes out-of-the-box with powerful and advanced models and offers facility functions and for the data science process. 
We'll learn and use other modules along the road, for a quick usage just look at their official documentation. 


### End-to-End Machine Learning project 

For a first taste, i suggest you to go through this Kaggle notebook, which is the most classic example of ML task. The goal is trying to predict if a Titanic passenger would have been most likely to survive or not. Many things will be unclear for now, but don't worry, they will be all explained comprehensively later. Is nice to get the picture of the "applied" project, going through the classical steps of the applied Machine Learning (problem framing, data exploration, question forumlation...)

The notebook is on [Kaggle](https://www.kaggle.com/), the go-to platform for ML and general Data Science projects, which provides a lot of free datasets and offers interesting challenges and ML model experiments.

[This](https://www.kaggle.com/startupsci/titanic-data-science-solutions) is the notebook: Read it, trying to get the big picture of the process, because some details, functions and code will be clearer later.

### Linear Regression
This is the simplest form of Machine Learning, and the starting point for everyone interested in predicting outcomes from a dataset.
Check [here](https://www.youtube.com/watch?v=W46UTQ_JDPk&list=PLoR5VjrKytrCv-Vxnhp5UyS1UjZsXP0Kj&index=2) the theoretical lesson from Andrew NG and then go through these examples, from the simplest to the most complete.\
[This](https://www.geeksforgeeks.org/ml-normal-equation-in-linear-regression/) is the math behind Linear Regression.\
- [Example 1](https://scikit-learn.org/stable/auto_examples/linear_model/plot_ols.html#sphx-glr-auto-examples-linear-model-plot-ols-py)\
- [Example 2](https://bigdata-madesimple.com/how-to-run-linear-regression-in-python-scikit-learn/)\
- [Example 3](https://www.geeksforgeeks.org/linear-regression-python-implementation/)

### Classification
Classification is one of the most important ML tasks, and want to predict an outcome classifying it among differente possibilities. For example, given handwritten numbers, classify them with the lowest error possible.
The simplest case is binary classification (Yes or No, Survived or Not Survived), have a look [here](https://machinelearningmastery.com/make-predictions-scikit-learn/).
Check [here](https://towardsdatascience.com/building-a-logistic-regression-in-python-301d27367c24) a brief explanation of the theory of logistic regression algorithm for classification, and check [here](https://www.youtube.com/watch?v=VCJdg7YBbAQ) for a deeper comprehension (using the Titanic dataset).
You can use a lot of different ML models to classify things, even neural networks! For now, just take a look [here](https://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html), where you see an example of comparison among different models accuracy and recall.
[Here](https://medium.com/thalus-ai/performance-metrics-for-classification-problems-in-machine-learning-part-i-b085d432082b) you have an article about the metrics used to **evaluate** your classifiers.

### Training models
Here i grouped some of the techniques used in ML tasks to train the models.
In this Google Crash Course you find:
- [Gradient Descent](https://developers.google.com/machine-learning/crash-course/reducing-loss/gradient-descent)
- [Learning Rate](https://developers.google.com/machine-learning/crash-course/reducing-loss/learning-rate)
- [SGD](https://developers.google.com/machine-learning/crash-course/reducing-loss/stochastic-gradient-descent)
- [Regularization](https://www.youtube.com/watch?v=Q81RR3yKn30)

### Support Vector Machines
### Decision Trees
### Ensemble Learning and Random Forest 

-----------------------------------------------------------------

## Neural Networks with TensorFlow
### Why TensorFlow?
### Up and Running with TensorFlow
### ANN - Artificial Neural Networks 
### CNN - Convolutional Neural Networks
### RNN - Recurrent Neural Networks
### Training Networks: Best practices 
### AutoEncoders
### Reinforcement Learning
