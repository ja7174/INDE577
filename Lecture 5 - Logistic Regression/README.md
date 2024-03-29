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

1a. determine its species with a choice between Adelie and Chinstrap using logistic regression<br>
1b. determine whether increasing features reduces error <br>



### Method

Like linear regression, logistic regression computes the weighted sum of the input features. Unlike linear regression, however, this sum is then passed through the sigmoid function to output the logistic of the result. The sigmoid function, outputs a number between 0 and 1 (a probability) which is then used to predict if the a datapoint belongs to the specific class.