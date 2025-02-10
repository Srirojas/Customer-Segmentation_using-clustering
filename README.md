# Customer Segmentation using Clustering

## Project Overview
This project performs Customer Segmentation using K-Means Clustering to identify distinct customer groups based on their purchasing behavior. By analyzing Age, Annual Income, and Spending Score, we can segment customers and develop targeted marketing strategies.

## Objective
- Understand customer shopping behaviors using clustering techniques.
- Apply K-Means Algorithm to segment customers into distinct groups.
- Perform Feature Engineering, Normalization, and PCA for optimal clustering.

## Dataset
Features Considered: Numerical Variables being Age, Annual Income (k$), Spending Score (1-100) & Categorical Variable being Gender (encoded)
Excluded Feature: CustomerID (Not relevant for clustering)

## Exploratory Data Analysis (EDA)
✔ Data Normalization – Standardizing numerical features for better clustering
✔ Encoding Categorical Variables – Converting Gender into numerical values
✔ Principal Component Analysis (PCA) – Reducing dimensionality for visualization
✔ WCSS (Within-Cluster Sum of Squares) & Elbow Method – Finding optimal clusters

## Machine Learning Model: K-Means Clustering
Applied K-Means Clustering to segment customers based on their purchasing patterns.

## Finding the Optimal Number of Clusters
- Used Elbow Method to determine the best k value.
- WCSS plot shows an "elbow" at k=4, meaning the data naturally segments into 4 clusters.
  
## Elbow Method Visualization

## Cluster Analysis
- After applying K-Means, 4 distinct customer segments are identified.
- Cluster Visualization using PCA

## Technologies Used
- Python 
- Pandas – Data Processing
- Matplotlib – Data Visualization
- Scikit-learn – Clustering & PCA
