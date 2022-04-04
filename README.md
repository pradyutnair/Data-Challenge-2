# LSTM Neural Network

This branch contains an LSTM model used for forecasting the crimes.

## Phase 1 
Like ARIMA, conduct univariate time series analysis (`Univariate LSTM Analysis.ipynb`). This means using only the total crimes to predict the total crimes.

## Phase 2
Test baseline, bidirectional and convolutional LSTM model. Plot the loss per epoch and benchmark each model against the baseline model.

## Results
The model failed to generalise to the data in both univariate and multivariate cases. The evaluation metrics are also very high in contrast to the ARIMA model. This can be seen in the picture below-
![lstm](https://user-images.githubusercontent.com/83001928/161606770-daf3e589-d1b9-4cac-95fc-3e0e2aee8d3e.png)

Therefore, the LSTM model was discarded.

## Contributors
[Pradyut Nair](https://github.com/pradyutnair) \
[Lieve Göbbels](https://github.com/Lieve2) 




