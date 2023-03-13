# Predicting the Cooling Load of Buildings
## By Godswill Sedem Buabassah

## Introduction

>The study is focused on using machine learning to assess the cooling load requirements of buildings (that is, energy efficiency) as a function of building parameters.


## The Dataset

>The dataset was obtained from the UCI Machine learning repository https://archive.ics.uci.edu/ml/datasets/energy+efficiency

>The dataset contains eight attributes (or features, denoted by X1...X8) and two responses (or outcomes, denoted by Y1 and Y2). The aim is to use the eight features to predict the response Cooling Load(Y2).
Specifically:

|Variable||Attributes|
|-----||----|
|X1||Relative Compactness|
|X2||Surface Area|
|X3||Wall Area|
|X4||Roof Area|
|X5||Overall Height|
|X6||Orientation|
|X7||Glazing Area|
|X8||Glazing Area Distribution|
|y1||Heating Load|
|y2||Cooling Load|


## Conclusion

>The GradientBoostingRegressor was selected as the best model for predicting the cooling load of buildings based on the given parameters of this dataset. This model was selected because it gave the highest r2_score of 0.99.





```python

```
