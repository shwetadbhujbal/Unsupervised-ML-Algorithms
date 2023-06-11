# Unsupervised-ML-Algorithms
Building Unsupervised Machine Learning Algorithms from Scratch


## 1. K Means Clustering Algorithm:

K-Means clustering is one of the most popular and simplest clustering algorithms. The value 'K' in the K-means algorithm denotes the number of clusters. In k-means data is divided into k clusters where each cluster has a centroid which is basically the average of all the points in the cluster.
K-Means assign only one cluster to each point.

### Lloyd’s algorithm (K-means algorithm)
This algorithm is used to cope with the problem of updating the centers. It has 4 basic steps:
➔ Initialization: Randomly initialize k centers from the dataset.
➔ Assignment: For each point, we find the distance of existing centroids from it and assign the point to that cluster whose centroid has the minimum distance.
➔ Update the centroids of the clusters by taking the average of points from each cluster.
➔ Repeat the previous two steps until convergence (the center of new cluster centroids stops changing their positions).




