# Project-5-MNIST-Handwritten-Digit-Recognition-using-Sklearn-and-LogisticRegression

## Introduction:
This is the famous MNIST Machine Learning project in which we have to predict handwritten digits. The dataset used in this project is taken from kaggle.

### Digit Recognition System
Digit recognition system is the working of a machine to train itself or recognizing the digits from different sources like emails, bank cheque, papers, images, etc. and in different real-world scenarios for online handwriting recognition on computer tablets or system, recognize number plates of vehicles, processing bank cheque amounts, numeric entries in forms filled up by hand.

## Problem Statement:
This is the famous MNIST Machine Learning project in which we have to predict handwritten digits.

## Requirements:
- Jupyter Notebook

## MNIST Dataset:
Samples provided from MNIST (Modified National Institute of Standards and Technology) dataset includes handwritten digits total of 70,000 images consisting of 60,000 examples in training set and 10,000 examples in testing set, both with labeled images from 10 digits (0 to 9). This is a small segment form the wide set from NIST where size was normalized to fit a 2020 pixel box and not altering the aspect ratio. Handwritten digits are images in the form of 28 * 28 gray scale intensities of images representing an image along with the first column to be a label (0 to 9) for every image. The same has opted for the case of the testing set as 10,000 images with a label of 0 to 9.

![](https://corochann.com/wp-content/uploads/2017/02/mnist_plot-800x600.png)

## Logistic regression:
Logistic regression is another technique borrowed by machine learning from the field of statistics.

It is the go-to method for binary classification problems (problems with two class values). In this post you will discover the logistic regression algorithm for machine learning.
Logistic Function
Logistic regression is named for the function used at the core of the method, the logistic function.

![](https://i0.wp.com/www.insightsbot.com/wp-content/uploads/2018/12/841495d7-0747-450a-a26b-4ae0e3eef6af.jpg?fit=432%2C288)

### Logistic function
The logistic function, also called the sigmoid function was developed by statisticians to describe properties of population growth in ecology, rising quickly and maxing out at the carrying capacity of the environment. It’s an S-shaped curve that can take any real-valued number and map it into a value between 0 and 1, but never exactly at those limits.

1 / (1 + e^-value)

Where e is the base of the natural logarithms (Euler’s number or the EXP() function in your spreadsheet) and value is the actual numerical value that you want to transform. Below is a plot of the numbers between -5 and 5 transformed into the range 0 and 1 using the logistic function.
![](https://3qeqpr26caki16dnhd19sv6by6v-wpengine.netdna-ssl.com/wp-content/uploads/2016/03/Logistic-Function.png)

### Representation Used for Logistic Regression
Logistic regression uses an equation as the representation, very much like linear regression.

Input values (x) are combined linearly using weights or coefficient values (referred to as the Greek capital letter Beta) to predict an output value (y). A key difference from linear regression is that the output value being modeled is a binary values (0 or 1) rather than a numeric value.

Below is an example logistic regression equation:

y = e^(b0 + b1*x) / (1 + e^(b0 + b1*x))

Where y is the predicted output, b0 is the bias or intercept term and b1 is the coefficient for the single input value (x). Each column in your input data has an associated b coefficient (a constant real value) that must be learned from your training data.

The actual representation of the model that you would store in memory or in a file are the coefficients in the equation (the beta value or b’s).

## Importing the Modules:
- Numpy
- Matplotlib
- Sklearn


## Score:
For this model, the accuracy on the test set is **0.97**, which means the model made the right prediction for **97%** of the handwritten digits in the given dataset. We can expect the model to be correct **97%** of the time for predicting the handwritten digits.

## Summary:
The MNIST handwritten digit recognition (and our implementation) is a perfect example to illustrate how a machine learning problem should be approached and how useful the outcome could be for computer vision.
