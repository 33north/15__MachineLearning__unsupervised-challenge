# 15__MachineLearning__unsupervised-challenge

We took cryptocurrency data from CryptoCompare and performed unsupervised machine learning on it.

We began with preprocessing the data by removing any currencies that were not being traded.  We got rid of currencies that had any null values.  We then filtered the currencies that were being mined.  Removed the coin names from the dataframe.  One-hot encoded the columns that had categorical data and finally standardized the data.

From there we performed a principal component analysis and a t-SNE to see if the data can be clustered.  We also ran a k-means clustering as well.

Based on the PCA, t-SNE model, k-means clustering there appears to be a distinguishable way to cluster the cryptocurrencies.  It's possible to cluster the cryptocurrencies into 4-5 clusters.  Based on the elbow graph, we can see there is a bend at 4 clusters and a bend at 5 clusters.  Therefore, the cryptocurrencies can be clustered together.