# Store-Sales-Prediction-Regression-TimeSeriesAnalysis-LP3

This repository contains the following files :

A document that presents our methodology and results :
Supermarket chain Favorita stores sales prediction
Jupyter notebooks for Python code:
FavoritaEDA_001.ipynb (complete preprocessing and model training)
Data files:
train.csv

The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.

store_nbr identifies the store at which the products are sold.

family identifies the type of product sold.

sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).

onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.

test.csv

The test data, having the same features as the training data. You will predict the target sales for the dates in this file.

The dates in the test data are for the 15 days after the last date in the training data.

transaction.csv

Contains date, store_nbr and transaction made on that specific date.
sample_submission.csv

A sample submission file in the correct format.
stores.csv

Store metadata, including city, state, type, and cluster.

cluster is a grouping of similar stores.

oil.csv

Daily oil price which includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and its economical health is highly vulnerable to shocks in oil prices.)
holidays_events.csv

Holidays and Events, with metadata
