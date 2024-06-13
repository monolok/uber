## Notebooks

### 1. eda.ipynb
This notebook includes exploratory data analysis where different dataframes are created for each day of the week and for different times of the day (morning, afternoon, etc.). Data points are visualized using Plotly's scatter_mapbox.

### 2. Kmeans_test.ipynb (centroi)
In this notebook, K-means clustering algorithm is applied to identify clusters, particularly focusing on hot zones. However, K-means is found to be less suitable for this specific problem as it assumes spherical clusters due to its reliance on minimizing Euclidean distances (like birds) from centroids. The data points are projected on a scatter_mapbox plot to illustrate this limitation.
n_clusters=5

### 3. dbscan_daily.ipynb
DBSCAN is utilized in this notebook. DBSCAN is particularly effective for this clustering problem because it does not assume spherical clusters and can find arbitrarily shaped clusters based on density (like differentiating main streets from others). This makes it more suitable for identifying hot zones or irregularly shaped clusters within the data.
eps=0.0008, min_samples=50

### 4. dbscan_time_of_the_day.ipynb
Extra stuff