# car-price-prediction:
## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Approach](#Approach)
 * [Data Preprocessing](#Data-Preprocessing)
 * [Feature Selection](#Feature-Selection)
 * [Model Implementation](#Model-Implementation)




## Problem Statement:
This is a Machine learning project with linear regression and lasso.i am trying to predict the car price by the training the dataset.

![b82e14cf-3c85-4f91-84c0-bea095c353a8](https://github.com/arshad33199/car-price-prediction/assets/142779412/6c969547-9f7a-45ce-9371-dcd1f72fad18)

## Approach:

## Data Preprocessing:
In this section I am doing all the Data cleaning and analysis.Most of the data is in categorical form which should get converted into numerical form. 

I did some feature engineering in it and encoding the types.There are many columns which i created from the existing column which you can see in the notebook.

I checking different car names and calculate it.



This all the process i followed for test dataset as well and made a training and test dataset to feed in the Machine learning algorithm.


## Feature Selection:

Finding out the best feature which will contribute and have good relation with target variable. Following are some of the feature selection methods.

(1) Heatmap

![download](https://github.com/arshad33199/car-price-prediction/assets/142779412/2ad5780f-8596-42db-bc74-9d32885fbd54)


## Model Implementation:

I used Linear regression to fit the dataset.

The R2 square values which i got is 87.99% 

![download (1)](https://github.com/arshad33199/car-price-prediction/assets/142779412/f14bc013-aef8-49f9-982a-21db07806cc3)




I also used Lasso to fit the dataset

The R2 square values which i got is 84.27% 

![download (2)](https://github.com/arshad33199/car-price-prediction/assets/142779412/b13db457-2b51-476c-b371-31ff4d89df90)
