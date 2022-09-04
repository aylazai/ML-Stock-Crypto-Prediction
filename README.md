# ML-Stock-Crypto-Prediction

## Summary

This script is a machine learning logistic regression model used to predict stock prices (or rather returns) in Python.

## The Model

In a nutshell, this model is a classification model which takes the prior N days' assets directions and predicts the return. Whether the return is positive or negative determines the direction of the assets. If the predicted direction is positive the asset will be bought or held, if it's negative the asset is assumed to be shorted.

#### Dependent Variable = Direction of the asset (+/-)
#### Independent Variable =  Prior *N* Days Directions

## Assumptions

Note I've assumed there are no trading costs to simplify the problem.
