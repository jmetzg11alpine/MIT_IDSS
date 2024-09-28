# k-means clustering (Lloyd's algorithm)
assign each point to the nearest centroid, update the centroid with the mean of the assign points, repeat until centroid doesn't move

ELBOW method to find the indeal amount of clusters

Assumptions:
- you know k in advance
- any data point can be expressed as a list of continuous values
- equally sized clusters

Goal:
- minimize the global disimilarity, which is the summation of disimilarity of clusters which are the summation of a data points from a centroid

# Principal Component Analysis (standard and fast)
a preprocessing step, reduce the number of features - project that spreads data as much as possible 

get the two largest iegenvalues from the correlation (features have the same weights) matrices to plot in two dimensional space

e.g - if you have many data points that are correlated then you can use PCA to reduce the number of features while still keeping the most of the variance

# Stochastic neighbor embedding (t-SNE, newer method)
non-linear embedding that tries to keep close-by points close