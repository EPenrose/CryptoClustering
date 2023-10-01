# CryptoClustering

#Summary:
The Crypto Clustering initiative aims to use unsupervised learning techniques, specifically K-means clustering, to predict whether changes in cryptocurrency prices over a 24-hour or 7-day period have an impact. Additionally, the project explores how reducing dimensions through Principal Component Analysis (PCA) influences the clustering results.

#Process:

Import and preprocess the dataset.
Normalize the data using StandardScaler.
Determine the optimal k-value using the elbow method.
Apply K-means clustering to the original scaled data.
Implement Principal Component Analysis (PCA) to reduce the feature set to three principal components.
Find the best k-value using the PCA-transformed data.
Cluster cryptocurrencies using K-means with the PCA-processed data.
Visualize and compare the results using hvPlot.
Conclusion:
This project examines the impact of feature reduction on data clustering with K-means. By comparing the clustering results between the original dataset and the PCA-processed data, it sheds light on how dimensionality reduction affects the clustering process.

#Language and Libaries
Python
pandas
NumPy
scikit-learn
hvPlot
