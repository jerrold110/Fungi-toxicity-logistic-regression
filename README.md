# Fungi-toxicity-logistic-regression
Classifying the probability of whether a mushroom specimen is poisonous or edible with variance analysis for feature selction and logistic regression machine learning.

This data mining project is the second attempt of my previous endeavor to classify the toxicity of mushroom specimens based on data of their physical characteristics such as colour, shape, and size, using Logistic Regression rather than discrete class label machine learning classifiers. The reason being that in reality a probability classifier is a safer approach to classifying the toxicity of objects meant for consumption because it reduces the risk of consuming a wrongly classified object. 

(a) Mushroom records drawn from The Audubon Society Field Guide to North American Mushrooms (1981). G. H. Lincoff (Pres.), New York: Alfred A. Knopf
(b) Donor: Jeff Schlimmer (Jeffrey.Schlimmer@a.gp.cs.cmu.edu)
(c) Date: 27 April 1987

I will attempt to classify the edibility of fungi specimens based on 22 different physical characteristics. The dataset has over 8124 rows of data with 23 columns, each representing the physical data of a fungi specimen. This is an entirely categorical dataset with a binary class label: poisonous or edible - which poses some difficulties in training a machine learning model. About one quarter of the data has missing values which were estimated using data from other rows rather than just simply being removed. There are two parts in this project.

Data understanding and cleaning:
* Exploratory data analysis 
* Feature selection with variance analysis
* Data cleaning with machine learning

Data Modelling:
* Pre-processing with one-hot-encoding
* Logistic Regression modelling and evaluation
* Hyperparameter tuning with Cross-Validation

