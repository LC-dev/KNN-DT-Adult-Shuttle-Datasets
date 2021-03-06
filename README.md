# KNN-DT-Adult-Shuttle-Datasets

## Project Status ð

Completed ð

## Table of Contents ð

* [Project Objectives](#objectives)
* [Methods](#methods)
* [Technologies](#tech)
* [Results](#results)
* [Setup](#setup)
* [Credits](#cred)

<a name="objectives"></a>
<a name="methods"></a>
<a name="tech"></a>
<a name="results"></a>
<a name="setup"></a>
<a name="cred"></a>

## Project Objectives â 

First ML project!

Machine learning models that predict whether a given adultâs salary is > $50K, and the type of control to apply on a given shuttle.
Explore preprocessing of the data, the effect of hyperparameters, size of the dataset, and performing model selection.

## Methods âï¸

* Data preprocessing
* Data visualization
* Hyperparameter tuning (5-fold cross-validation)
* Model selection

## Technologies ð»

* Python 3.7.12
* sklearn
* numpy
* pandas
* matplotlib
* scipy

## Results ð

Optimal models found for:
* Adult dataset 
  * KNN: 85.2% accuracy, unweighted K=21, non-normalized data
  * DT: 86.1% accuracy, maximum_depth=10, Gini index, non-normalized data
* Shuttle dataset
  * KNN: 99.9% accuracy, weighted K=6, both normalized and non-normalized
  * DT: 99.9% accuracy, max_depth=6, Entropy, both normalized and non-normalized data

## Setup ð©âð»

* Clone this repo
* Install dependencies if needed
* Run the notebook

## Variables â¨ï¸
```
dataset1_train = pd.read_csv('insert path of adult_train.csv',...)
dataset1_test = pd.read_csv('insert path of adult_test.csv',...)
dataset2_trn_full = pd.read_csv('insert path of shuttle_trn.csv',...)
dataset2_test = pd.read_csv('insert path of shuttle_tst.csv',...)
```

## Credits ð

Thank you to my amazing team for working on this project! 
