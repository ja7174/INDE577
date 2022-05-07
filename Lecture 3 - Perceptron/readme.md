# Data Science & Machine Learning
## The Perceptron

### Dataset Used
Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network. The datasets are available for download and use [here](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data). 

### Libraries Used
[Pandas] (https://pandas.pydata.org/)
[Matplotlib] (https://matplotlib.org/)
[Numpy] (https://numpy.org/)
[Seaborn] (https://seaborn.pydata.org/)
[Scikit-learn] (https://scikit-learn.org/)

### Task

Given the bill length and bill depth of a pengiun, classify

1a. whether the species is Adelie or Gentoo
1b. whether the species is Gentoo or Chinstrao

### Method

The Perceptron is used on binary classification problems. Thus, we need to choose two of the three species of penguin to implement and train the perceptron on it. For the first task, we use the species Adelie and Gentoo while for the second task we use Gentoo and Chinstrap.

The perceptron can take in any number of feature measurments, but for simplicity we focus our attention on just two feature measurements, namely "bill_length_mm" and "bill_depth_mm".

The perceptron is a single neuron model with the sign activation function. 
The activation function is how the input data will be interpreted. The activation function associated with the perceptron is the sign activation function, which classifies any output less than 0 as -1, and any output greater than or equal to 0 as 1.

Once the model has been trained on one segment of the data. We test it on the remaining data. This is particularly important to check for overfitting.






