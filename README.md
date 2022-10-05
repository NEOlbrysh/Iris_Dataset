# Iris_Dataset

## Introduction
The Iris flower data set is a popular multivariate dataset created by British statistician and geneticist Ronald Aylmer Fisher, as an example of discriminant analysis.
The central goal is to design a model that makes proper classifications for new flowers.
The Iris dataset is a classic dataset for classification, machine learning, and data visualization.
The dataset contains: 3 classes with 50 samples each, and then four numeric properties about those classes: Sepal Length, Sepal Width, Petal Length, and Petal Width.
One species, Iris Setosa, is "linearly separable" from the other two. This means that we can draw a line between Iris Setosa samples and samples corresponding to the other two species.

## Alogorthiums
- Support-Vector Machines (SVM)- Support vector machine is highly preferred by many as it produces significant accuracy with less computation power. Support Vector Machine, can be used for both regression and classification tasks. But, it is widely used in classification objectives.
- K-nearest neighbors algorithm (K-NN)- algorithm is an index-based algorithm. It uses a non-parametric method for classification or regression. Training with the k-NN algorithm has three steps: sampling, dimension reduction, and index building, the main objective of k-NN's training is to construct the index.
- Decision Tree Classifier- can perform both classification and regression tasks. The intuition behind Decision Trees is that you use the dataset features to create yes/no questions and continually split the dataset until you isolate all data points belonging to each class.

## Exploratory Data Analysis
EDA is a technique used to analyze data using some visual Techniques.

- Scatterplots use a collection of points placed displaying values from two variables. By displaying a variable in each axis, you can detect if a relationship or correlation between the two variables exists.

-Seaborn Jointplot creates a scatter plot with two histograms at the top and right margins of the graph by default. 

- Seaborn Heatmap
Python seaborn heatmap is a graphical representation of 2D data. Each data value represents in a matrix and it has a special color. The main intention of Seaborn heatmap is to visualize the correlation matrix of data for feature selection to solve business problems.

- FacetGrid class helps in visualizing distribution of one variable as well as the relationship between multiple variables separately within subsets of your dataset using multiple panels.

## Predicted Attribute:
Class of Iris plant.


## Purpose

The dataset consists of 150 cases (rows) and 5 variables (columns) named Sepal.Length, Sepal.Width, Petal.Length, Petal.Width, and Species of three species of the Iris flower: the Iris setosa, the Iris virginica and the Iris versicolor. 

This discriminant analysis produces a simple function that, given the four measurements, will classify a flower correctly.

The purpose of this project was to gain introductory exposure to Machine Learning Classification concepts along with data visualization. The project utilizes Scikit-Learn, Pandas and Data Visualization Libraries.


### AWS:
https://s3.console.aws.amazon.com/s3/buckets/neo-iris?region=us-east-2&tab=objects

## Sources:

https://archive.ics.uci.edu/ml/datasets/Iris

https://www.researchgate.net/figure/Iris-data-set-There-are-three-classes-Setosa-class-is-linearly-separable-from-the-other_fig2_300643220
