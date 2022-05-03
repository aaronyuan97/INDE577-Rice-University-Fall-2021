# K-means  
K-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. 

Unlike supervised learning, unsupervised learning deals with *unlabeled* data. As such, the techniques used are vastly different than those found in supervised learning. Unsupervised learning typically falls within the following two reahlms:

1. **Clustering**

2. **Dimensionality Reduction** 

To process the learning data, the K-means algorithm in data mining starts with a first group of randomly selected centroids, which are used as the beginning points for every cluster, and then performs iterative (repetitive) calculations to optimize the positions of the centroids

![alt](https://i2.wp.com/dataaspirant.com/wp-content/uploads/2020/12/1-K-means-Clustering.png?w=750&ssl=1)
## How the K-means works
The working of the K-Means algorithm is explained in the below steps:

Step-1: Select the value of K, to decide the number of clusters to be formed.

Step-2: Select random K points which will act as centroids.

Step-3: Assign each data point, based on their distance from the randomly selected points (Centroid), to the nearest/closest centroid which will form the predefined clusters.

Step-4: place a new centroid of each cluster.

Step-5: Repeat step no.3, which reassign each datapoint to the new closest centroid of each cluster.

Step-6: If any reassignment occurs, then go to step-4 else go to Step 7.

Step-7: FINISH

## Datasets
make moon dataset from scikit learn
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_moons.html

## Packages
* matplotlib
* numpy
* pandas
* seaborn
* sklearn
