# Cryptocurrency Market Analysis
## Overview
This repository contains a Jupyter Notebook script for analyzing cryptocurrency market data using K-Means clustering and Principal Component Analysis (PCA). The analysis aims to identify patterns and group similar cryptocurrencies based on their price change percentages over a specific time period.

## Contents
- [Notebook File](notebook.ipynb): Jupyter Notebook containing the analysis code.
- [Data File](Resources/crypto_market_data.csv): CSV file containing the cryptocurrency market data.

## Dependencies
To run the analysis, you'll need the following dependencies:
- pandas
- hvplot
- scikit-learn
  
## Usage
1. Clone the repository to your local machine.
2. Install the required dependencies using pip.
3. Open and run the Jupyter Notebook (`notebook.ipynb`) using Jupyter Notebook or JupyterLab.
4. Follow the instructions in the notebook to load the data, preprocess it, perform K-Means clustering, and visualize the results.

## Analysis Steps
1. **Data Loading and Preprocessing**: Load the cryptocurrency market data from the CSV file and perform basic preprocessing steps such as scaling.
2. **Exploratory Data Analysis**: Generate summary statistics and visualize the data to understand its distribution and patterns.
3. **K-Means Clustering (Original Data)**: Use K-Means clustering to group cryptocurrencies based on their price change percentages. Determine the optimal number of clusters (k) using the Elbow method.
4. **Principal Component Analysis (PCA)**: Apply PCA to reduce the dimensionality of the data and visualize the explained variance ratio.
5. **K-Means Clustering (PCA Data)**: Repeat K-Means clustering using the PCA-transformed data and compare the results with the original data.
6. **Visualize and Compare Results**: Create visualizations to compare the clustering results obtained using the original data and PCA-transformed data.

## Results
The analysis reveals insights into the cryptocurrency market by identifying clusters of cryptocurrencies with similar price change patterns. The optimal number of clusters is determined using both the original data and PCA-transformed data, and the results are visualized for comparison.

## Conclusion
K-Means clustering and PCA are powerful techniques for analyzing and visualizing high-dimensional data such as cryptocurrency market data. By grouping cryptocurrencies into clusters, investors and analysts can gain insights into market trends and make informed decisions.
