# Cryptocurrencies

## Overview of the Project
The senior manager for the Advisory Services Team at Accountability Accounting is looking for help with a report of what cryptocurrencies are on the market and how they could be grouped. Because of the data available, it was decided that unsupervised machine learning would be best to create classifications. For the report, the following tasks were completed.

1. Prepare the data for dimension reduction and clustering.
2. Reduce data dimensions using PCA from sklearn.
3. Predict clusters using the K-means algorithm from sklearn.
4. Create 2D and 3D scatter plots and a data table to present the results.

## Resources
- Data source: crypto_data.csv
- Software: Python 3.7 using libraries: Pandas, Scikit-learn, hvplot and Plotly Express; Jupyter Notebook

## Summary of Results
The data was cleaned, scaled with StandardScaler and reduced to three principal components using PCA.
- The elbow curve showed a prominent bend at k = 4, so the K-means algorithm was run with 4 clusters.
- Most cryptocurrencies fit into two of the four clusters.
- Bittorrent had such large numbers, that it is in its own cluster.
- The table shows available cryptocurrencies; table is sortable and selectable.
