# KMeans
In Machine Learning there is supervised learning (data already with labels) and unsupervised learning (data without labels). KMeans is the latter. https://www.ibm.com/cloud/blog/supervised-vs-unsupervised-learning

This algorithm clusters data points based on Euclidean distance between data points and a random centroid in the data. Centroids get updated based on averages of datapoints and within a cluster. That average becomes the new centroid. 

Flow of Algorithm:

Randomize centroids

For each data point, assign data point to clusters (a centroid represents a cluster) based on Euclidean distance.
(Euclidean Distancerepresents similarities in data)

<img width="531" alt="Screen Shot 2022-08-31 at 11 37 29 AM" src="https://user-images.githubusercontent.com/63027273/187754248-362b97b3-14e3-459f-aaf2-75ced225145f.png">

Update centroids: 

For each cluster, get the average of all datapoints. 

Average = new center/centroid
