# CryptoClustering
 
## Overview
This project involves utilizing Python and unsupervised learning techniques to predict whether cryptocurrencies are affected by 24-hour or 7-day price changes. The primary goal is to apply clustering algorithms, such as K-Means, to identify patterns and group cryptocurrencies based on their price change behaviors.

## Dataset
The dataset used for this project is sourced from cryptocurrency market data. It includes features related to the percentage change in prices over various time intervals, such as 24 hours, 7 days, 14 days, 30 days, 60 days, 200 days, and 1 year. Each row in the dataset represents a different cryptocurrency.

## Tasks and Challenges

### Data Standardization:

Use the StandardScaler module from scikit-learn to normalize the data.
Create a DataFrame with the scaled and normalized data.

### Elbow Method for Optimal K:

Apply K-Means clustering with different values of k (number of clusters).
Use the elbow method to find the optimal value for k by analyzing the sum of squared distances (inertia).

### Cluster Analysis:

Visualize the clusters formed by K-Means on both the original data and the data after dimensionality reduction using Principal Component Analysis (PCA).
Analyze and compare the clustering results.


## Results
The project aims to provide insights into the clustering patterns of cryptocurrencies based on their price change behaviors. The results include visualizations of clusters and comparisons between clustering methods, such as K-Means on the original data and PCA-transformed data.

## References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
Refereces for the code: https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html
