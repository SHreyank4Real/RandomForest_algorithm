# Random Forest Algoritham

This README outlines the details of random forest algoritham in machine learning

## Prerequisites

You will need the following things properly installed on your computer.

* [python3.6](https://www.python.org/downloads/)
* numpy
* matplotlib 
* pandas
* dataset 

or you can use google colab notebook
* https://colab.research.google.com

## Explanation
Random forests start with the idea of decision tree. This is a way of making a decision based on a flow chart. The random forest is a way of making a decision based on votes from many decision trees which are created by using a subset of the attributes. We do this to prevent our decision trees from overfitting.
Suppose you have several models that each classify some data. The goal of the random forest is to minimize the prediction error in a "generalizable way", which means doing it with as few steps as possible. So we want to use each model's output so that it gives us the most information about the classification.

also see [this](https://www.youtube.com/watch?v=i8D90DkCLhI)

## steps
* Pick at random K data points from the training set.
* Build the decision tree associated to these K data points.
* Choose the number N tree of trees you want to build and repeat above steps.
* For a new data point, make each one of your trees predict the values of Y to for the data point in question and assign the new data point the average across all of the predicted Y values.
