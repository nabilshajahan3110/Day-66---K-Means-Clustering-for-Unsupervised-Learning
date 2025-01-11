## Day-66---K-Means-Clustering-for-Unsupervised-Learning
As part of a 75-day data analysis challenge, this work on Python deals with K-means clustering.

K-means clustering is a popular unsupervised machine learning algorithm used for partitioning a dataset into distinct groups (clusters) based on similarity. It aims to group data points such that points within the same cluster are more similar to each other than to points in other clusters.

### How K-means Works:

**1. Specify the number of clusters (k):** You need to define the number of clusters the algorithm should create.

**2. Initialize centroids:** Randomly initialize k centroids (center points of clusters).

**3. Assign data points to clusters:** For each data point, calculate the distance (e.g., Euclidean distance) to each centroid. Assign the point to the cluster whose centroid is closest.

**4. Update centroids:** Recalculate the centroid of each cluster as the mean of the points assigned to it.

**5. Iterate:** Repeat steps 3 and 4 until centroids stabilize (i.e., do not change significantly) or a maximum number of iterations is reached.

**Output:** The algorithm outputs the cluster assignments for each data point.

**Applications:**

Customer segmentation

Image compression

Document clustering

Market basket analysis

Anomaly detection

**Advantages:**

Simple and computationally efficient for small datasets.

Works well when clusters are well-separated and spherical in shape.

**Limitations:**

You need to predefine the number of clusters (k).

Sensitive to initialization and outliers.

Assumes clusters are of similar size and density.
