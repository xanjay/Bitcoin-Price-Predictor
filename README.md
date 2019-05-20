# Bitcoin Price Predictor
Bitcoin price predictor using Recurrent Neural Network (LSTM)

## Task: Regression
Predict next day opening price from last 60 days price. 
## Data:
The csv file contains columns: time, low, high, open, close, volume.
Only "open" value is used.
## Data Preprocessing:
- Scaled using sklearn.preprocessing.StandardScalar.
- Create sequence of last 60 values as input and take next value as target.
## Network Configuration:
- Stacked LSTM
- Batch Normalization
- Dropout Regularization
- Adam Optimizer
