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

Given one or more features of a Gentoo penguin,

1a. estimate it's body mass <br>
1b. choose which feature best estimates body mass <br>
1c. investigate ideal rate for alpha (the learning rate)<br>
1d. identify and observe limitations for the simplified model <br>


### Method

One of the primary problems machine learning can tackle is to predict an outcome for a given set of inputs. A classic example of regression is predicting the body mass of a penguin based its features (i.e. bill length, bill depth, flipper length, sex etc.). This is determined by identifying the "best-fit" line of the data to minimize some cost function. <br>

Regression algorithms apply a function to input data to produce a prediction. This prediction is then compared to the real value (when training or testing) to calculate the error, and the weights adjusted (when training) to produce the optimal function that minimizes the error. To evaluate the performance of an algorithm, the data is segmented so the model has not been exposed to every element. This allows us to see how accurate a prediction will be compared to an actual label.