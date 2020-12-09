# Clustering Stocks with K-Means Algorithm

## Basic Overview:

* **Goal**: Create an algorithm that helps financial experts to categorize stocks with particular attributes in a specific cluster.

* Stock selection, outlier detection, portfolio creation are important mechanisms for the financial industry to maximize and strategize the right investments in the stock market. Therefore, using certain indicators (often latent factors) we would attempt to cluster the given stocks to enable data driven decision making.

* Clustering will help in pointing common attributes/characteristics the clustered stocks share.

------


## Why K-Means clustering?

* K-Means is one of the easiest clustering algorithm to understand. The understanding behind the algorithm also enabled me to find right methods to clean & prepare the data along with selecting the right hyperparamaneter for the algorithm.

* This understanding of the algorithm ensures that K-Means will be optimized in the right way to find structure in this unstructured stocks data.

* K-Means will ensure minimum distance between the data points and the K-centroids.

------

## Resources and code used:

* ***Python Version***: 3.8
* ***Packages***: Pandas, Matplotlib, Axes3D from mpl_toolkits, Numpy, Normalizing tools (MinMaxScaler, RobustScaler, StandardScaler), Sklearn (PCA, KMeans, Metrics)
* ***Data Source***: TD AmeriTrade (https://www.tdameritrade.com/api.page)
* ***Stock Domain Knowledge 101***: [Source 1](https://www.researchgate.net/publication/4885243_Stock_selection_based_on_cluster_analysis), [Source 2](http://people.stern.nyu.edu/adamodar/New_Home_Page/data.html)
* ***YouTube***: [Source 1](https://www.youtube.com/c/SigmaCoding/videos), [Source2](https://www.youtube.com/watch?v=EItlUEPCIzM)

------

## Data Acquisition:

* Accesed the TD AmeriTrade API to request stock data
* Used 'request' library to enable API data acquisition

## Data Cleaning:
