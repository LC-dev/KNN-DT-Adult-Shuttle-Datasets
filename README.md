# KNN-DT-Adult-Shuttle-Datasets

## Project Status 🕒

Completed 🙌

## Table of Contents 📜

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

## Project Objectives ✅ 

First ML project!
Explore preprocessing of the data, the effect of hyperparameters, size of the dataset, and performing model selection.

## Methods ✍️

* Data preprocessing
* Data visualization
* Hyperparameter tuning (5-fold cross-validation)
* Model selection

## Technologies 💻

* Python 3.7.12
* sklearn
* numpy
* pandas
* matplotlib
* scipy

## Results 📈

Optimal models found for:
* Adult dataset 
  * KNN: 85.2% accuracy, unweighted K=21, non-normalized data
  * DT: 86.1% accuracy, maximum_depth=10, Gini index, non-normalized data
* Shuttle dataset
  * KNN: 99.9% accuracy, weighted K=6, both normalized and non-normalized
  * DT: 99.9% accuracy, max_depth=6, Entropy, both normalized and non-normalized data

## Setup 👩‍💻

* Download ```results.ipynb```,```data``` & dependencies
* Insert datasets and notebook in the same folder
* Run the notebook

## Variables ⌨️
```
dataset1_train = pd.read_csv('insert path of adult_train.csv',...)
dataset1_test = pd.read_csv('insert path of adult_test.csv',...)
dataset2_trn_full = pd.read_csv('insert path of shuttle_trn.csv',...)
dataset2_test = pd.read_csv('insert path of shuttle_tst.csv',...)
```

## Credits 🏅

Thank you to my amazing team for working on this project! 
