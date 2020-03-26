LSTM homework.

In this Homework I created an LSTM model to help predict Bitcoin closing prices and an FNG Sentiment score.

my model included :
a 70/30 split of the data
1,000 nodes
0.78 dropout fraction
5 total layers
24 epochs

The total loss from closing price Model was 0.005432320388742477

The total loss from FNG score was 0.08269625577641411

using the Bitcoin SEntiment was not a god fit for the model to predict the value of Bitcoin. The LSTM Model used with the closing price gave us the better outcome prediction. 

Also, chaning the window size rounded the prediction values out (less noise/error)