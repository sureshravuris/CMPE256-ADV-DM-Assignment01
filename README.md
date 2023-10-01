# CMPE256-ADV-DM-Assignment01

# **Hierarchical Clustering Methods**

Hierarchical clustering is a method of cluster analysis that seeks to build a hierarchy of clusters. The endpoint is a set of clusters, where each cluster is distinct from each other cluster, and the objects within each cluster are broadly similar to each other.

This repository covers three primary hierarchical agglomerative (bottom-up) clustering methods:
1. Single-Link (Minimum Linkage) Clustering
2. Complete-Link (Maximum Linkage) Clustering
3. Average-Link Clustering

# Introduction:
Agglomerative clustering works by treating each data point as a single cluster initially and then repeatedly merging the closest pair of clusters into larger clusters, until all points have been merged into a single remaining cluster.

# Methods:

**Single-Link Clustering:**
In single-link clustering, the distance between two clusters is defined as the shortest distance between two points in each cluster. It can result in elongated clusters where two clusters can be linked by a single pair of points that are close to each other while other points in the clusters might be much further away from each other.

**Complete-Link Clustering:**
In complete-link clustering, the distance between two clusters is defined as the longest distance between two points in each cluster. This tends to produce more compact, equally-sized clusters.

**Average-Link Clustering:**
In average-link clustering, the distance between two clusters is defined as the average distance between each point in one cluster to every point in the other cluster. This method provides a balance between the single-link and complete-link methods.
