# Comparison Models
This branch contains two models that were used for a comparison against ARIMA and LSTM models.

## OLS
In the `OLS.ipynb`, it becomes evident that regression is not a suitable choice for this forecasting task. This is because the variables are not very correlated and 
regression fails since it relies on exactly that. The predictions for the multivariate case are poor. However, although not satisfactory, OLS does a fair job in univariate prediction.

![ols](https://user-images.githubusercontent.com/83001928/161608460-d9fbc32b-9e86-4e34-aea9-85ddaf9bc3a9.png)

## Prophet
Facebook's Prophet model is a powerful neural network that is geared towards the goal of this project. However, due to explanability and implementation issues, its use was discarded in preliminary Sprints.



## Contributors
[Mahmut Can Aridasir](https://github.com/mahmutcan1) \
[Pradyut Nair](https://github.com/pradyutnair) 
