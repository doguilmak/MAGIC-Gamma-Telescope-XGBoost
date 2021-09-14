# Predict Gamma (signal) and Hadron (background) from MAGIC Gamma Telescope with XGBoost


## Problem Statement

The purpose of this study is to predict the result of the telescope observation. Algorithm is trying to predict the class (11th row) which is gamma (signal) or hadron (background). 

## Dataset

Dataset is downloaded from [archive.ics.uci.edu](https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope) website. You can find the details of the dataset in that website. Dataset has **11 columns** and **19020 rows without the header**.

## Methodology

In this project, as stated in the title, results were obtained through **XGBoost** method.  You are free to visit [XGBoost](https://xgboost.ai/) website for learn the method better.

## Analysis

***Confusion Matrix(XGBoost):***
| 3807 | 481 |
|--|--|
| **251** | **1700** |


> **Accuracy score(XGBoost): 0.8826735053694502**
> 
> **Process took 0.8865966796875 seconds.**

## How to Run Code

Before running the code make sure that you have these libraries:

 - pandas 
 - time
 - sklearn
 - numpy
 - warnings
 - xgboost
    
## Contact Me

If you have something to say to me please contact me: 

 - Twitter: [Doguilmak](https://twitter.com/Doguilmak).  
 - Mail address: doguilmak@gmail.com
