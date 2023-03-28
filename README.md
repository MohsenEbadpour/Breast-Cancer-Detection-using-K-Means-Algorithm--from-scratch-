# Breast Cancer Detection using K-Means Algorithm 
This repository contains code for a problem related to implementing and investigating the k-means algorithm in pattern recognition. The problem involves implementing the k-means algorithm for breast cancer diagnosis, evaluating its accuracy, and exploring the impact of different initialization methods on clustering results.

## Course Information

This problem is related to a *Statistical Pattern Recognition* course taught by Professor Mohammad Rahmati (<rahmati@aut.ac.ir>) in the Computer Engineering department at Amirkabir University of Technology (AUT) in Tehran, Iran. The course was offered in the Fall of 2021.

## Problem Description
In this question, the goal was to use K-Means clustering to diagnose breast cancer based on the features obtained from fine needle aspiration (FNA) images. The following tasks were performed:

a. A function named kmeanscluster was implemented that took in a data matrix X, the number of clusters k, the initial centers mu, tolerance parameter tol, and maximum number of iterations maxIter. The clustering result was stored in matrix C, and the accuracy of the clustering was calculated.

b. The kmeanscluster function was run 5 times with different starting points, and the accuracy of each case was calculated. The observations were noted and explained.

c. The kmeanscluster function was run using the provided initial centers stored in init_mu.mat, and the accuracy of the clustering was reported.

d. The effect of initializing with the true centers obtained after the true clustering was analyzed.


![Output](/output.png)


## Repository Contents

The repository contains Python code for the problem described above, as well as a Jupyter notebook that explains the problem and provides a step-by-step cells for running the code.

## Feedback

If you have any feedback or suggestions for improving this code, please feel free to open an issue in the repository as well as send an email to Mohsen Ebadpour (<m.ebadpour@aut.ac.ir> , <mohsenebadpour@outlook.com>).




