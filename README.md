# Clustering

### Programing Language:
Python

### Purpose:
This program explores the Iris dataset (loaded from sklearn datasets). <br>
It performs principal component analysis (PCA) and k-means clustering.

### Requirements:
* pandas
* numpy
* matplotlib.pyplot
* sklearn.datasets
* sklearn.cluster
* sklearn.decomposition
* sklearn.preprocessing
* seaborn
* scipy.cluster.hierarchy
* scipy.cluster.vq 
* yellowbrick.cluster

### How it works:
This program explores the iris dataset. <br>
It performs a brief statistical summary of the the variables and plots the distribution of all four variables (predictors). <br>

A kmeans elbow plot is rendered to determine the optimum number of clusters <br>

A comparison is then performed between the clustern of the full dataset and the PCA reduced dataset. <br>

To verify the number of clusters a dendrogram is rendered using the variance minimization algorithm.
