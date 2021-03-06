# Dimensionality-Reduction

Here Dimensionality reduction is done on mnist data set where its a collection of hand written digits (28 *28 ). => 784 dimensions.

# PCA

PCA is one of the way to reduce high dimension features (say 784 in MNIST dataset in our example) to lower dimension without losing the variance of the original data.

Steps to arrive PCA:
lets take our dataset as matrix A

Step 1: Preprocess A i.e standardize the dataset.
Step 2 : Find the co-variance of the A , let's say co-variance matrix as S.
Step 3: Find the eigen values and eigen vectors for the co-variance matrix, S
Step 4 : Find the dot product of the eigen vector and co-variance matrix , S

Eigen Values - Gives us the percentange of variance of the features
Eigen Vectors - Gives us the direction of the features .



# t-SNE

(t-SNE) t-Distributed Stochastic Neighbor Embedding is a non-linear dimensionality reduction algorithm used for exploring high-dimensional data. It maps multi-dimensional data to two or more dimensions suitable for human observation. With help of the t-SNE algorithms, you may have to plot fewer exploratory data analysis plots next time you work with high dimensional data.
