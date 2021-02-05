# Unsupervised Machine Learning and Cryptocurrencies

## Purpose
Accountaibility Accounting, a hypothetical investment bank, wants to offer a new cryptocurrency investment portfolio and need a report including the cryptocurrencies that are currently being traded on the market and how they could be separated into groups. By first reducing dimensions and using the K-means algorithm, I created visualizations in order to share my findings with the board.

## Results
- Using te Elbow Curve, I found that the best value for K was 4
- Below is a screenshot of the 3D-Scatter plot of the clusters and the PCA data:

<img src='https://github.com/npantfoerder/cryptocurrencies/blob/master/kmeans_clusters.png' width=500>

### Resources
- Data Source: crypto_data.csv from CryptoCompare (https://min-api.cryptocompare.com/data/all/coinlist)
- Software: Python 3.7.3, Anaconda 4.8.3, hvPlot 0.6.0, Scikit-learn 0.23.1, Plotly 4.12.0
