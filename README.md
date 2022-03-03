# Cryptocurrencies 

## Overview
On this project I used unsupervised machine learning to learn about a set of cryptocurrencies, in hopes to find some worth investing in. 

## Results
First I cleaned the data by: removing null values, keep only curriencies that are trading, and dropping unnecesary columns. Then, I used get_dummies to create variables for the text features. Once the data was clean, I scaled the data with StandardScaler and then used PCA to reduce the features to 3. With the information we created a new DF and clustered the data using K-means, before jumping to the visualization. 

## Summary
A 3-D scatter was created as well as a scatterplot. The final result shows 532 tradeable currencies, less than half of what the original dataset had. 