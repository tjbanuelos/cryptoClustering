# cryptoClustering

This repository is a clustering analyis of several crypto currencies using Machine Learning tools. First we normalize the data using Standard Scalar and then use an Elbow Curve to identify the optimal k-value for our analysis. Once we run our KMeans algorithm to produce our clusters, we then use PCA to reduce our data set to 3 dimensions. Once again we use an Elbow Curve to identify and the KMeans algorithm to give us a clear visual while preserving most of our data integrity (approx 90% of variability preserved). Finally we look at our graphs side by side to asses how well our algorithms performed. 

In this directory you will find the following documents. 

A jupyter notebook containing all the machine learning analysis titled 'Crypto_Clustering.ipynb'
A csv file containing crypto currency market data titled 'crypto_market_data.csv'
