# Welcome

# Syllabus

## 1: Intro

Getting to know each other, discussing the plan, the guidelines for sharing the assignments, etc.

Going through a small demo/tutorial for Jupyter Notebooks. See [demo notebook here](1. Intro to Jupyter Notebooks - Python.ipynb).


## 2: Linear Regression

Create simple prediction models from small datasets. See [demo notebook here](2. Linear Regression - Python.ipynb)

### Recommended datasets: 
* [House prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data): Predict the price of a house based on surface, lot size, #bathrooms, #bedrooms, etc.
* [Titanic survivability](https://www.kaggle.com/c/titanic): Predict the likelyhood of someone surviving the sinking of the Titanic based on their gender, age, passenger class and some other variables.
* [Video Game sales with ratings](https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings): Predict how well a game will sell based on the critic rating, user rating, publisher and genre.


## 3: Binary Classification

Go over binary classification problems and some algorithms for solving them, e.g logistic regression. See [demo notebook here](3. Binary Classification - Python.ipynb)

### Recommended datasets:

* [Medical Appointment No Shows[(https://www.kaggle.com/joniarroba/noshowappointments): predict whether a patient will show up for his scheduled appointment
* [Rotten Tomatoes moview reviews](https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews): predict whether the review is positive or not (ant not the score itself).
* [Amazon Fine Foods reviews](http://snap.stanford.edu/data/web-FineFoods.html): multivariate regression: predict whether the review is positive or not *and* whether other users find it helpful.
* [Credit card fraud detection](https://www.kaggle.com/dalpozz/creditcardfraud): predict whether a transaction is fraudulent or not.
* [HR Analytics - When will an employee leave the company](https://www.kaggle.com/ludobenistant/hr-analytics): predict whether an employee is likely to leave the company.


## 4: Clustering

Solve some simple clustering prodblems with K-nearest neighbors/K-means. See [demo notebook here](4. Clustering - Python.ipynb)


## 5: Recommendations

Create a model for product recommendations with collaborative filtering. See [demo notebook here](5. Collaborative Filtering - Python.ipynb)


# Datasets

There's no machine learning without something to learn. This section contains a list of places where you can find datasets useful for a ML study group / course / training.

* [Kaggle Datasets](https://www.kaggle.com/datasets): Large collection of datasets, many of them already explored and explained by other community members.
* [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.html): Loads of datasets, with the suitable technique (regression, classification, etc) pointed out for each of them.
* [Google research datasets](https://research.google.com/research-outreach.html#/research-outreach/research-datasets)
* [AWS-hosted Public Datasets](https://aws.amazon.com/public-datasets/): Quite large datasets, but many interesting ones containing real world data
* https://datahub.io
* [The default sci-kit learn datasets](http://scikit-learn.org/stable/datasets/)
* [mldata.org dataset repository](http://mldata.org/repository/data/)

# Theory

There are many sources that cover the theory of machine learning. 

## Full courses

* [MIT 6.034 Artificial Intelligence, Fall 2010 - MIT OpenCourseWare](https://www.youtube.com/playlist?list=PLUl4u3cNGP63gFHB6xb-kVBiQHYe_4hSi)

## Books

* [Machine Learning: Hands-On for Developers and Technical Professionals - Jason Bell, 2014](https://www.amazon.de/gp/product/1118889061/ref=oh_aui_detailpage_o02_s01?ie=UTF8&psc=1): A book that touches many of the ML techniques in a developer-friendly way, with working code examples.

* [Machine Learning: From Theory to Algorithms - Shai Shalev-Shwartz, Shai Ben-David, 2014](https://www.amazon.de/gp/product/1107057132/ref=oh_aui_detailpage_o02_s00?ie=UTF8&psc=1): This book explores most machine learning branches in great depth, with the caveat of also being very theory-heavy. Better get a refresh on your greek alphabet before diving in. 


## Cheatsheets

Diagrams that assist you in choosing the correct model to train:
* [scikit-learn - Choosing the right estimator](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
* [Machine learning algorithm cheatsheet for Microsoft Azure ML Studio](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-algorithm-cheat-sheet)

Note: these only hint the correct algorithm to use for a particular situation and are still useful regardless of the platform one uses.

# Libraries

## Integrated offline environments

* [Anaconda](https://anaconda.org): Simple way to offline install Python, Jupyter Notebooks and all required libraries for data science & machine learning. Should work for other languages besides Python (R, Ruby, Scala, Java, JS) but untested. Feel free to add details here if you've tried it.
* [RStudio](https://www.rstudio.com): Very nice IDE for R

## Online Environments

* [Kaggle](http://kaggle.com/): Online hosting of Jupyter Notebooks. Supports Python (2?) and R.
* [Azure Notebooks](https://notebooks.azure.com/): Online hosting of Jupyter Notebooks. Supports Python 2&3, R and F#
* [Anaconda Cloud](https://ananconda.org): Packages must be developed offline, but can then be uploaded to Anaconda Cloud and shared with everyone.

## Python

* [scikit-learn](http://scikit-learn.org/stable/)
* [pandas](http://pandas.pydata.org/)
* [SFrame](https://github.com/turi-code/SFrame)
* [pytorch](https://github.com/hughperkins/pytorch)

## Java/.NET/R/Lua/Others

To anyone interested in using any of these: Feel free to add dedicated sections.


# Other Tools

* [Gist](https://gist.github.com): Preferred way of sharing code snippets.

* [Jupyter Notebook viewer](http://nbviewer.jupyter.org): Allows viewing of Jupyter notebooks from any URL, github repo or gist.

# Related Subjects

## Statistics

Highly recommended course available for free on Coursera: [Basic Statistics, by University of Amsterdam](https://www.coursera.org/learn/basic-statistics/home/welcome)

Statistics cheatsheets:
* http://web.mit.edu/~csvoss/Public/usabo/stats_handout.pdf
* http://cs229.stanford.edu/section/cs229-prob.pdf

