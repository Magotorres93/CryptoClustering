# CryptoClustering

In this challenge, we’ll use our knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
First we prepared the Data
We used the StandardScaler() module from scikit-learn to normalize the data from the CSV file and we created a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
We found the Best Value for k Using the Original Scaled DataFrame and then we cluster cryptocurrencies with K-means Using the Original Scaled Data.
After we optimized the Clusters with Principal Component Analysis and found the Best Value for k Using the PCA Data


