# Data Science & Machine Learning
## The Perceptron

### Dataset Used
Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network. The datasets are available for download and use [here](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data). 

### Libraries Used
[Pandas](https://pandas.pydata.org/) <br>
[Matplotlib](https://matplotlib.org/) <br>
[Numpy](https://numpy.org/) <br>
[Seaborn](https://seaborn.pydata.org/) <br>
[Scikit-learn](https://scikit-learn.org/) <br>

### Task

Given the bill length and bill depth of a pengiun, classify

1a. whether the species is Adelie or Gentoo <br>
1b. whether the species is Gentoo or Chinstrao <br>

### Method

The Perceptron is used on binary classification problems. Thus, we need to choose two of the three species of penguin to implement and train the perceptron on it. For the first task, we use the species Adelie and Gentoo while for the second task we use Gentoo and Chinstrap.

The perceptron can take in any number of feature measurments, but for simplicity we focus our attention on just two feature measurements, namely "bill_length_mm" and "bill_depth_mm".

The perceptron is a single neuron model with the sign activation function. 
The activation function is how the input data will be interpreted. The activation function associated with the perceptron is the sign activation function, which classifies any output less than 0 as -1, and any output greater than or equal to 0 as 1.

We begin with randomly selected values for the weights that we continuosly update at every iteration. This update rule for the weights is done on the basis of an alpha value (the learning rate) and the difference of the predicted value with the true value. This part of the algorithm is done on one segment of the data - the training data.

Once our error (or in this case misclassification rate) is significantly low or plateus, we stop iterating.

Once the model has been trained on one segment of the data. We test it on the remaining data (called the test data). This is particularly important to check for overfitting.






