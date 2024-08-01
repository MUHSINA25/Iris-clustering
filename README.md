# clustering-techniques-to-a-real-world-dataset
#### The Iris Dataset
This data sets consists of 3 different types of irises’ (Setosa, Versicolour, and Virginica) petal and sepal length, stored in a 150x4 numpy.ndarray

The rows being the samples and the columns being: Sepal Length, Sepal Width, Petal Length and Petal Width.

The below plot uses the first two features. See [here](https://en.wikipedia.org/wiki/Iris_flower_data_set) for more information on this dataset.


#### K-Means Clustering:

K-Means algorithm is an iterative algorithm that tries to partition the dataset into K
pre-defined distinct non-overlapping subgroups (clusters) where each data point belongs
to only one group. It tries to make the intra-cluster data points as similar as possible
while also keeping the clusters as different (far) as possible. It assigns data points to a
cluster such that the sum of the squared distance between the data points and the
cluster’s centroid is at the minimum. The less variation we have within clusters, the
more homogeneous the data points are within the same cluster.
We then proceeded to perform K-means Clustering which will create different
clusters to group similar spending activity based on their age and annual income. KMeans Clustering selects random values from the data and forms clusters assigned. The
closest values from the centre of each cluster were taken to update the cluster and
reshape the plot (just like k-NN). The closest values are based on Euclidean Distance.
