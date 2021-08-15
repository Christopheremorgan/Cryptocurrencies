# Cryptocurrencies

## Overview of the analysis: 
This analysis clusters cryptocurrencies leveraging data from CryptoCompare to inform how an investment bank develops and offers a new cryptocurrency investement portfolio for their clients.

## Data Preprocessing & Principal Component Analysis 
Pandas and scikit-learn libaries were used to prepare the data for Principal Component Analysis to reduce the number of dimension upon which to cluser the cryptocurrencies.

## K-Means Clustering & Visualizing Results
The K-Means clustering algorithm in scikit-learn was used to assign classes to each cryptocurrency and then plotly and hvplot were used to visualize cluster results.


An elbow curve was plotted to help identify the number of groups to cluster the cryptocurrencies. For this analysis the K-Means algorithm was run with k=4.
![image_name](https://github.com/Christopheremorgan/Cryptocurrencies/blob/main/elbow_curve.png)


Once each cryptocurrency was assigned to a class, the clusters were plotted on a 3-D interactive scatter plot.  The chart can be rotated and information about each cryptocurrency appears when hovering over their data point.
![image_name](https://github.com/Christopheremorgan/Cryptocurrencies/blob/main/3D_scatter.png)


## Jupyter Notebook File
[crypto_clustering.ipynb](https://github.com/Christopheremorgan/Cryptocurrencies/blob/main/crypto_clustering.ipynb)




