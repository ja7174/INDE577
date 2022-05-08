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

1a. compare and visualize the performance of a random forest on Adelie vs. Chinstrap classification <br>
1b. compare and visualize the performance of a Bagging on Adelie vs. Chinstrap classification <br>
1c. compare and visualize the performance of a ADA Boosting on Adelie vs. Chinstrap classification <br>
1d. compare and visualize the performance of other classifiers on Adelie vs. Chinstrap classification <br>

### Method

Ensemble learning is the combination of multiple models to determine the final value of a prediction. Each model developed to model data has benefits and issues. Ensemble learning seeks to maintain the benefits of a model and mediate the issues. Ensemble learning can be used for regression and classification tasks, and can consist of multiple instances of the same model, or any combination of task-specific models (i.e. classification or regression).

#### Random Forest

A random forest is a collection of decision trees. Random forests build decision trees from drawing samples (without replacement) from the dataset. This tactic decreases the variance of the forest estimator and mitigate the risk of overfitting. The average of the decision trees is taken, averaging out some errors, to produce a prediction.

#### Bagging

Bootstrapping is a method of inferring results for a population from results found on a collection of smaller random samples of that population, using replacement during the sampling process. In the context of machine learning, a given set of machine learning model is trained respectively on random samples of training data with replacement (see the above figure), then the combined predictions of each model is aggregated and used as a single prediction.

#### ADA Boosting

With AdaBoost, the training algorithm first trains a base classifier and uses it to make predictions on the training set. Then, each of the missclassified training instances is then given a relative weight. The next classifier is then trained on the dataset using these relative weights, and so on. The idea is that whenever a classifier missclassifies a data point,this data point is then boosted to signal difficulty in classification.






