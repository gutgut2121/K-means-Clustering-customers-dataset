# K-means-Clustering-customers-dataset

This project focuses on performing K-means clustering on a dataset of customers using two attributes: standardized income and standardized age. The goal is to cluster the customers into 3 distinct groups using the K-means algorithm and Euclidean distance. The initial centroids for the clusters are set to A, D, and H.
These attributes (standardized income and standardized age) allow for a meaningful analysis of customer segments based on their financial status and age group.

# K-means Clustering Steps
The K-means clustering algorithm involves the following steps:

Initialization: K initial centroids are assigned to the dataset.
Assignment: Each observation is associated with the nearest centroid, creating K clusters.
Update: The centroid of each cluster is recalculated based on the observations assigned to it.
Convergence Check: If the centroids do not converge, the algorithm returns to step 2 for further iterations.
Throughout this project, these steps will be followed to perform K-means clustering on the customers dataset, aiming to identify distinct customer groups based on their income and age attributes.
