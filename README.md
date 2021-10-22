# Stock-price
Stock market prediction using ANN
This repository contains the python code for stock market prediction using ANN. The datasets used is Google stock market price taken from kaggle. The project uses keras to import layers into the ANN and matplotlib for the plots. We add a layer of LSTM followd by a dropout layer which leaves some of the neurons during the prediction. This removes the problem of overfitting by redcing complex coadaption. The training using the data from past 60 days and using the data of 61st day as the output. 
