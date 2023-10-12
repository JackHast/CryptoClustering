# CryptoClustering

## Summary

The purpose of this repository is to use KMeans to cluster the change in the price of a number of cryptocurrencies over time periods ranging from 24 hours to 1 year.
Initially, the data was standardised and the elbow method was used to determine the optimal number of clusters. It was determined that this method was not able to properly cluster the data points
and so principal component analysis (using 3 principal components) was performed on the dataframe df_market_data.

## Contents of Repository

This repository contains a Jupyter Notebook "Crypto_Clustering.ipynb" and a folder "Resources" that contains a csv file "crypto_market_data.csv" used in the Jupyter Notebook.

## Instructions

In order to run the Jupyter Notebook contained in this repository, the entire repository must be downloaded and the following libraries must be installed, <br>

-  hvplot
- scikit-learn

## Acknowledgements

Starter code for this assignment was provided by the Monash University Data Analytics Bootcamp: https://bootcamps.monash.edu/data/