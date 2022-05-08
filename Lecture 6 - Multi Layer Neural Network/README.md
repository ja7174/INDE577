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

1a. prepare a feature vector using all possible information available in the data set <br>
1b. instantiate and train a multi-layered neural network <br>
1c. comment on the performance of the network using the testing data <br>

### Method

The Multilayer Perceptron, or MLP, is an artificial neural network composed of at least three perceptron layers - an input layer, a hidden layer, and an output layer. While the input and output layers are only one level deep, the hidden layer can contain any number of layers. A MLP containing a "deep" stack of hidden layers is called a Deep Neural Network. A deep stack is a succession of hidden layers where the output of one feeds the input of the next. MLPs can also have wide layers where the input layer, for example, feeds hidden layer 1 and the output layer. This is a wide network because it connects all or part of the inputs directly to the output layer. This allows the network to learn both deep patterns and simple rules.
