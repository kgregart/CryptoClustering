# Crypto Clustering with Machine Learning

##Objective

###Predict if cryptocurrencies are affected by 24-hour or 7-day price changes through unsupervised machine learning using Python.

![cryptocurrency_price_change_graph](https://github.com/kgregart/CryptoClustering/assets/153472472/fb900b58-26e9-4525-bc46-c3787ba6d145)


##Instructions

###1. Prepare the Data:  Load, scale and create a DataFrame

###2. Find the best value for k using the original scaled DataFrame applying the elbow method to find the best value for k.

###3. Cluster Cryptocurrencies with K-means using the original scaled data.

###4. Optimize clusters with Principal Component Analysis
###using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.

###5. Find the best value for k with the PCA data using the elbow method to find the best value for k.

###6. Cluster Cryptocurrencies with K-means using the PCA data to find the best value for k.


##Libraries and Dependencies 

###Pandas
###Pandas Hvplot
###Sklearn 
###Sklearn Decopmpostition
###Sklearn Preprocessing

##Questions and Answers

###What is the best value for k?
###What is the total explained variance of the three principal components?
###What is the best value for k when using the PCA data?
###Does it differ from the best k value found using the original data?
###What is the impact of using fewer features to cluster the data using K-Means?

##Conclusion
