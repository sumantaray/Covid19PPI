# Covid19

Code for Ncov2-Human PPI Interactor Link Prediction

Prepare the Adjacencymatrix.csv file.

Run  ISMBcode.py script directly on the above adjacency matrix.

The user input for #Number of Features to be selected using the algorithm. 

Output **Feature_Matrix** is the feature representaion of each node. 

Then Lovain clustering is mployed on Feature_Matrix. 

Three similarity measures are computed on each cluster, then rank aggregation is applied to obtain aggregated neighbor protein list of each SARS-Cov-host protein.

The Predicted indirect interactions between human proteins and SARS-CoV2 proteins are given in **S1** file.

## Pre-requisites

> Python version  3.3


> Python Packages: pandas, node2vec, numpy, sklearn
