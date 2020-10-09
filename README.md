# clustering
clustering in Data science

# Problem Statement
Customer segmentation lies at the heart of every consumer facing business nowadays which involves being able to identify different types of customers and then figuring out ways to find more of those individuals so you can… you guessed it, get more customers!
In this assessment, you'll be doing exactly that, albeit with the help of K-Means clustering and observe how you can form groups of customers exhibiting similar behaviour.

# What is Clustering?
Clustering is the process of dividing the entire data into groups (also known as clusters) based on the patterns in the data.


# Types of Clustering

Broadly speaking, clustering can be divided into two subgroups :

## Hard Clustering: 
In hard clustering, each data point either belongs to a cluster completely or not. For example, in the above example each customer is put into one group out of the 10 groups.

## Soft Clustering: 
In soft clustering, instead of putting each data point into a separate cluster, a probability or likelihood of that data point to be in those clusters is assigned. For example, from the above scenario each costumer is assigned a probability to be in either of 10 clusters of the retail store.


# Types of clustering algorithms

## Connectivity models
Examples of these models are hierarchical clustering algorithm and its variants

## Centroid models
 K-Means clustering algorithm is a popular algorithm that falls into this category.
 
## Distribution models
For example: Normal, Gaussian

## Density Models
For example : DBSCAN and OPTICS


# In this notebook decribed KMeans Clustering:
# How K-Means actually works?
Step 1: Choose the number of clusters k
Step 2: Select k random points from the data as centroids
Step 3: Assign all the points to the closest cluster centroid
Step 4: Recompute the centroids of newly formed clusters
Step 5: Repeat steps 3 and 4

# Stopping Criteria for K-Means Clustering
1. Centroids of newly formed clusters do not change
2. Points remain in the same cluster
3. Maximum number of iterations are reached


# How to Choose the Right Number of Clusters in K-Means Clustering?
![Inertia](https://github.com/maha-prathamesh/clustering/blob/main/Inertia.png)
 
