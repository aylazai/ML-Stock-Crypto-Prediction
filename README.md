# ML Stock and Crypto Prediction

This project is a Python script that uses machine learning logistic regression to predict stock and crypto prices (or rather returns). The model is based on a classification model that takes the prior N days' asset directions and predicts the return. The direction of the asset determines whether it should be bought or sold.

## Model Overview

The model uses logistic regression, a type of supervised learning algorithm used for classification, to predict the direction of the asset (+/-) as the dependent variable. The independent variable is the prior N days' asset directions. The logistic regression model uses a sigmoid function to produce a probability score, which is then thresholded to determine the predicted direction of the asset. 

## Technologies Used

The project uses the following technologies:

- Python
- NumPy
- Pandas
- scikit-learn

## Assumptions

Note that this model assumes that there are no trading costs to simplify the problem. Additionally, the model focuses on predicting asset returns rather than absolute prices.


## Future Work

This project can be further improved by using more advanced machine learning algorithms such as neural networks and decision trees. Additionally, incorporating more features such as volume and news sentiment can improve the accuracy of the model.
