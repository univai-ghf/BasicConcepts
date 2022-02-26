# Overfitting and Regularization: Basic Concepts of Machine Learning

This workshop has 2 aims. It (a)aims to introduce the basic concepts of machine learning and (b)utilize these concepts in choosing a machine learning model.

The basic problem with models that are too complex in machine earning is that they are not robust. This is called over-fitting. We will see two ways to fix this: choosing a model of an appropriate complexity, called *complexity control*, or choose a very complex model to begin with and restrict this model's parameters to a subset of their allowed values, called *regularization*.

In both these approaches, there are hyper-parameters whose values must be set. And these values are determined on sets called validation sets, while the fitting is done on the training set, for reasons we shall see.

Workshop: [![Open Workshop In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/univai-ghf/BasicConcepts/blob/main/basic_concepts.ipynb)

Finally, a homework problem on classification with Logistic Regression and k-Nearest Neighbors will help cement your understanding.

Homework: [![Open Homework In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/univai-ghf/BasicConcepts/blob/main/homework_knnClassification.ipynb)
