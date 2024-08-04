# Crypto Market Data Analysis

## Introduction
This project aims to analyze cryptocurrency market data to identify patterns and insights using Principal Component Analysis (PCA) and K-Means Clustering. The goal is to reduce the dimensionality of the data and cluster the cryptocurrencies into meaningful groups.

## Dataset
- **crypto_market_data.csv**: Contains historical price change percentages of various cryptocurrencies.

## Methods
### Data Preprocessing
- The data was scaled using `StandardScaler` from scikit-learn.

### Principal Component Analysis (PCA)
- PCA was performed to reduce the data to three principal components.
- The total explained variance of the three principal components is 89.5%.

### K-Means Clustering
- The Elbow method was used to determine the optimal number of clusters.
- K-Means clustering was performed with three and four clusters.

## Results
### PCA Results
- The three principal components explained 89.5% of the variance.
- ![alt text](image.png)

### K-Means Clustering Results
- The optimal number of clusters was found to be three.
- [Include any relevant visualizations or tables]

### Feature Influence
- Features with the strongest influence on each principal component were identified.
- [Include any relevant tables or summaries]

## Conclusion
- The analysis revealed distinct clusters of cryptocurrencies based on their price change percentages.
- PCA helped in reducing the dimensionality and capturing the most important features.

## Files in the Repository
- `crypto_market_data.csv`
- `Crypto_Clustering.ipynb`
- `README.md`
- `LICENSE`

## How to Run the Code
1. Clone the repository.
2. Install the required libraries: `pandas`, `scikit-learn`, `hvplot`.
3. Run the Jupyter Notebook: `Crypto_Clustering.ipynb`.

## License
This project is licensed under the Unlicence License.

## Acknowledgements
- Special thanks to the instructional team for their support.
