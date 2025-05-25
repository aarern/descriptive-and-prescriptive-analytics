# Cluster Analysis

This project analyzes stock market data using clustering techniques to uncover patterns among companies based on financial metrics. 
The data is first standardized to ensure comparability across variables like Price, Dividend Yield, and Market Cap. 
Hierarchical clustering is performed using the Manhattan distance and Ward’s method, with dendrograms used to visualize the structure. 
K-means clustering is then applied to segment the data into distinct groups, and the elbow method is used to determine the optimal number of clusters. 
The final clusters are visualized using fviz_cluster() to better understand the composition of each group.

