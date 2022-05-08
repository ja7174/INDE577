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

Given two features of a penguin and using the K-nearest neighbours algorithm

1a. classify a data point as either Adelie or Chinstrap<br>
1b. analyze how many neighbours give the lowest error<br>
1c. compare the performance of KNN with other classifier like logistic and MLP <br>

### Method

The K-Nearest Neighbors (KNN) algorithm is a machine learning model in which a specified number of neighbors (k) are calculated to determine the classification of the feature vector in question. KNN can be use for both classification and regression tasks. 

In classification, a vote is taken amongst the neighbors, and the classification with the highest vote wins. In regression, the average of the k-neighbors is taken as the predicted value of the feature vector. In the case where k=1, the classification or value of the closest neighbor becomes the classification or value of the feature vector.

Neighbors can also be assigned higher weights the closer they are to the datapoints to perform weighted neighbor classification. 