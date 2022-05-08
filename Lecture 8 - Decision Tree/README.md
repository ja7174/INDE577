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

1a. classify between Adelie and Chinstrap using a decision tree<br>
1b. comment on its performace using the test data <br>

### Method

Decision tree classifiers are an evolution of the classification chart.  The decision tree is a model that predicts the value of a target variable based on input variables. Each node in the tree is labeled with an input feature and the arcs of the feature are labeled with possible values (i.e. Bill length >= 1, bill depth =< 1). Each node splits possible values of each feature until arriving at a position in which (ideally) one class is described by the set of inequalities preceding the node. A decision the programmer must make is the acceptable mixture of classes within a leaf node. Only allowing pure nodes could expose the model to overfitting. This is an example of a greedy algorithm.

