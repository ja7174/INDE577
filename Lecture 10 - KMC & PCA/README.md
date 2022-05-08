# Data Science & Machine Learning
## The Single Neuron Linear Regression Model

### Dataset Used
Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network. The datasets are available for download and use [here](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data). 

### Libraries Used
[Pandas](https://pandas.pydata.org/) <br>
[Matplotlib](https://matplotlib.org/) <br>
[Numpy](https://numpy.org/) <br>
[Seaborn](https://seaborn.pydata.org/) <br>
[Scikit-learn](https://scikit-learn.org/) <br>

### Task

Given one or more features of a penguin,

1a. using the K-means clustering group the three species of penguin  <br> 
1b. using PCA try to establish a classification between the species <br>

### Method

#### K-Means Clustering

K-means clustering is an unsupervised machine learning algorithm used as a method of vector quantization that attempts to partition a dataset into k clusters. A feature vector is assigned to the closest cluster centroid. This algorithm minimizes the variance within a cluster by optimizing the squared errors of the feature vectors in the cluster. This optimization is computationally difficult, however heuristics exist that that allow the algorithm to converge quickly to a local optimum.

Computing the centroids of K-means is easily understood. Centroids are randomly placed, typically by assigning them as a datapoint. It then computes the distance of each datapoint from its assigned centroid, and updates the centroid to minimize this distance. 

#### Dimensionality Reduction

PCA is the process of computing the process of computing the principal components and using them to perform a change of basis on the data. This method is commonly used for dimensionality reduction by projecting each datapoint onto only the first few principal components to obtain lower dimensionality. PCA can be thought of as fitting a n-dimensional ellipsoid to the data where each axis of the ellipsoid represents a principal component. If an axis of the ellipsoid is small, the variance along the axis is small. Essentially, PCA seeks to define a hyperplane to project data onto while preserving the variance of the data.