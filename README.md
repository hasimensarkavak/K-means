# K-Means Clustering From Scratch

K-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster.

## The 5 Steps in K-means Clustering Algorithm

* Step 1 => Randomly pick k data points as our initial Centroids.

* Step 2 => Find the distance (Euclidean distance for our purpose) between each data points in our training set with the k centroids.

* Step 3 => Now assign each data point to the closest centroid according to the distance found.

* Step 4 => Update centroid location by taking the average of the points in each cluster group.

* Step 5 => Repeat the Steps 2 to 4 till our centroids don’t change.

# Used

* Numpy
* Pandas
* Matplotlib