# Customer-Segmentation
## Project Overview
The Customer Segmentation using K-Means Clustering project is designed to group customers into distinct segments based on their purchasing behavior. By analyzing historical customer purchase data, this project helps businesses tailor their marketing strategies, improve customer service, and optimize product offerings.

## Features
### Customer Data Generation:
Creates synthetic customer data including annual_income and spending_score.
### Data Preprocessing:
Standardizes data to prepare it for clustering.
### Optimal Clusters Determination:
Uses the Elbow method to find the optimal number of clusters for K-Means.
### Clustering: 
Applies K-Means clustering to group customers into segments.
### Visualization:
Plots customer segments based on annual income and spending score.
### Evaluation: 
Computes the silhouette score to assess the quality of clustering.
Requirements
Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn
## Code Explanation
Data Generation: Generates a synthetic dataset with annual_income and spending_score for 1,000 customers.
### Data Preprocessing:
Scales the data to standardize features.
### Optimal Clusters Determination:
Uses the Elbow method to identify the optimal number of clusters.
### Clustering: 
Applies K-Means clustering with the optimal number of clusters.
### Visualization:
Creates scatter plots to visualize customer segments.
### Evaluation:
Calculates and prints the silhouette score to evaluate clustering performance.
