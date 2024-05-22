## SMOTE  study

Anonymous repository

## Table of Contents
  - [Getting Started](#getting-started)
  - [Data sets](#data-sets)
  - [Acknowledgements](#acknowledgements)

## Getting Started

If you want to reproduce our paper experiments:
  - the notebooks [here](notebooks/classif_experiments.ipynb) and [here](notebooks/distances_experiments.ipynb) reproduce the experiments
  - this [code](./validation) contains implementation of the the protocols used for the numerical experiments of our paper. 

In order to use our MGS strategy:
  - this [notebook](notebooks/resampling_example.ipynb) illustrates how to use it
  - the strategy is implemented [here](./oversampling_strategies/)

## Data sets

The data sets of used for our article should be dowloaded  inside the *data/externals* folder. The data sets are available at the followings adresses :

* [Pima](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
* Phoneme : https://github.com/jbrownlee/Datasets/blob/master/phoneme.csv 
* Abalone : https://archive.ics.uci.edu/dataset/1/abalone
* Wine : https://archive.ics.uci.edu/dataset/186/wine+quality
* Haberman : https://archive.ics.uci.edu/dataset/43/haberman+s+survival
* Yeast : https://archive.ics.uci.edu/dataset/110/yeast
* Vehicle : https://archive.ics.uci.edu/dataset/149/statlog+vehicle+silhouettes
* Ionosphere : https://archive.ics.uci.edu/dataset/52/ionosphere
* Breast cancer Wisconsin : https://archive.ics.uci.edu/dataset/15/breast+cancer+wisconsin+original
* CreditCard : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
* MagicTel : https://www.openml.org/d/44125
* California : https://www.openml.org/d/44090
* House_16H : https://openml.org/d/821 

For the vehicle data set, it is necessary to download all the *.dat* files from UCI Irvine and put them insie a folder named *vehicle*. then, this folder should be put inside the *data/externals* folder.
