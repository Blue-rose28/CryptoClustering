# CryptoClustering
## Usage
Open the _Crypto_Clustering.ipynb_ Jupyter Notebook to access the project code.
Run the cells in the notebook to perform the analysis and visualize the results.
Follow the step-by-step instructions in the notebook to replicate the analysis.
## Data
The project uses the crypto_market_data.csv file, which contains cryptocurrency market data with columns such as _coin_id, price_change_percentage_24h, price_change_percentage_7d_, and others.

## Analysis
The analysis is divided into several steps:
* Data preprocessing: Normalizing data using StandardScaler and creating DataFrames.
* Finding the optimal number of clusters using the Elbow method.
* Clustering cryptocurrencies using K-Means on the original data and PCA data.
* Visualizing the clustering results and comparing them.
## Results
The project provides insights into how cryptocurrencies can be grouped based on their price change percentages. It also demonstrates the impact of using PCA for dimensionality reduction in clustering.
