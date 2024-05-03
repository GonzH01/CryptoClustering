# Cryptocurrency Market Analysis
## Overview
The aim of this Jupyter Notebook script is to analyze cryptocurrency market data using K-Means clustering and Principal Component Analysis (PCA). The goal is to identify patterns and group together cryptocurrencies that exhibit similar behavior, with a focus on tracking their price changes over a specified period.

## Contents
- [Crypto_Clustering](notebook.ipynb): Jupyter Notebook containing the analysis code.
- [crypto_market_data](Resources/crypto_market_data.csv): CSV file containing the cryptocurrency market data.

## Dependencies
To run the analysis, you'll need the following dependencies:
- pandas
- hvplot
- scikit-learn
  
## Usage
1. Clone the repository to your local machine.
2. Install the required dependencies using pip.
3. Open and run the Jupyter Notebook (`Crypto_Clustering.ipynb`).
4. Follow the instructions in the notebook to load the data, process, perform K-Means clustering, and visualize the results.

## Conclusion
This study used K-Means clustering and Principal Component Analysis (PCA) on cryptocurrency market data to find important trends and patterns. Using PCA with K-Means can help simplify the data and find the best number of groups more easily. But, it might also make the results harder to understand and miss some important details. The best number of groups was found using both the original data and PCA, so we could compare the results well.
