# Crypto Clustering with Machine Learning

## Objective 

Predict if cryptocurrencies are affected by 24-hour or 7-day price changes through unsupervised machine learning using Python.

![cryptocurrency_price_change_graph](https://github.com/kgregart/CryptoClustering/assets/153472472/fb900b58-26e9-4525-bc46-c3787ba6d145)


## Instructions

1. Prepare the Data:  Load, scale and create a DataFrame

2. Apply the elbow method to find the best value for k using with the original scaled dataset put into a DataFrame.

3. Cluster Cryptocurrencies with K-means using the original scaled dataset.

4. Optimize clusters with Principal Component Analysis using the original scaled DataFrame and reduce the features down to three principal components.

5. Find the best value for k with the PCA data using the elbow method.

6. Cluster Cryptocurrencies with K-means using the PCA data.


## Dependencies 

+ Pandas

+ HVPlot

+ Sci-Kit Learn 


## Questions and Answers

1. What is the best value for k (original dataset)?

   The best value for 'k' is 4 clusters.
   ![elbow_curve_original_data](https://github.com/kgregart/CryptoClustering/assets/153472472/963d9e4d-7a95-4d7f-a4de-4c155ff9ec68)

3. What is the total explained variance of the three principal components?

   The total explained variance of the three principal components is 89.5% reducing the     
   overall accuracy by 10.5%.
   (Note: 0.3719856 + 0.34700813 + 0.17603793 = .89503166 or 89.5%)
   
5. What is the best value for k when using the PCA data?

   The best value for 'k' using the PCA data is 4 clusters.
   ![elbow_curve_pca_data](https://github.com/kgregart/CryptoClustering/assets/153472472/428111b9-4d69-4572-95f4-d664a4415a7d)

7. Does it differ from the best k value found using the original data?

   No, the number of clusters are the same among the two data sets.
   
9. What is the impact of using fewer features to cluster the data using K-Means?

   **Conlusion:**
   Visually analyzing and comparing the cluster analysis results illustrates   
   using the PCA data with fewer features is the ideal model for analysis as the tighter 
   clusters provide more defined segments.

   ![scatter_plot_original_data](https://github.com/kgregart/CryptoClustering/assets/153472472/59e3e105-aebb-4db3-9f20-abe6184eee15)

   ![scatter_plot_pca_data](https://github.com/kgregart/CryptoClustering/assets/153472472/993717db-d636-49fd-a72d-2a41e57e68a8)


