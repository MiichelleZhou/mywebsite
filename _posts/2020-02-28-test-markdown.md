---
layout: post
title: [Peer Review Paper] A Novel Spatial Clustering Method based on Delaunay Triangulation and Kernel Density
subtitle: Sihan Zhou, Guannan Wang
tags: [clustering, triangulation, KDE]
---
Commonly-used clustering algorithms tend to identify ellipsoidal, spherical, or other regularly-shaped clusters, but encounter difficulties when dealing with complex underlying groups that possess non-linear shapes, various densities, and noisy connections between multiple clusters. One particularly tricky problem is called touching issue, including adjacent problem, necking problem, chaining problem, etc. In this article, we formulate a graph-based, three-step clustering framework to solve those problems: density-based separation that takes kernel density estimation on each data point as criteria to create initial clusters with different density level, Delaunay triangulation based DBSCAN that uses the distribution of triangle area and edge length to handle the nonlinear shape of data and the touching issue, followed by KNN to deal with boundary points. 

