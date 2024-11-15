# CryptoClustering

This project explores clustering within a specific cryptocurrency market dataset provided in this repositoryt using unsupervised machine learning techniques, specifically K-Means clustering and Principal Component Analysis (PCA). By analyzing normalized metrics like price change percentages over various timeframes, distinct groupings could be identified in the data, uncovering potential patterns in cryptocurrency behavior.

## Key Objectives:
- Identify Optimal Clusters: Using the elbow method on both original and PCA-transformed data, I found the best value for k, balancing cluster compactness with interpretability.
- Implement K-Means Clustering: Clustering is applied to both the original scaled dataset and a reduced feature set from PCA, offering two different unsupervised perspectives on the crypto dataset.
- Visual Analysis of Clusters: Scatter plots visualize clusters across key metrics and principal components, while comparison plots reveal differences between different approaches to clustering.

## Results
The project compares clustering outcomes from the full dataset and PCA-reduced data, showing that PCA can simplify cluster structures and enhance visual clarity by focusing on principal trends. This approach helps clarify relationships among cryptocurrencies, although the reduction in features can also obscure certain nuanced details.


## Sources

- Most code was borrowed or inspired from class concepts taught in Module 19 of the June 2024 UMN Data Analytics Bootcamp course

- Chat GPT was used for review of structure in specific lines and for debugging
