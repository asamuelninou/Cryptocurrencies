# Cryptocurrencies
## Overview
With unsupervised machine learning with Principal Component Analysis and K Means I classified various cryptocurrencies and display the clustered results.

Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of your most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. I am hired to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Process
Utilizing ETL strategies I transformed current, activaly mined and traded cryptocurrencies for crypto algorithm and proof-type with the get_dummies() and StandardScaler() for the Principal Component Analysis algorithm with only 3 input components.

Using the Elbow Curve on the data, I found it best to use a KMeans of 4 to run the model.

Once the model was run, I created a comprehensive DataFrame with all the cryptocurrency information and the projected Classes from the Machine Learning model.

## Results
The 3 Dimensional Scatterplot shows that the KMeans of 4 was the right amount, even though there was one outlier in its own class: BitTorrent

I then created a 2 D Plot to show tradable coins by supply and number of coins mined.

## Summary
Based on the 2 D Plot, it would seem TurtleCoin would have the highest potential in investment, as its supply is high, although the number of coins mined is low.
Overall, I would question the accuracy of this model, since running the PCA Explained Variance Ratio, pca.explained_variance_ratio_, resulted in extremely low accuracy, below a 7% total.
