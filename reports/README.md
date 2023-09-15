# Clustering Report

## Scores

| Model                        | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|------------------------------|-------------|-------------------|----------------|
| KMeans                       | 0.5480      | 12366.4374        | 0.7560         |
| AgglomerativeClustering_Ward | 0.4083      | 10769.3204        | 0.9373         |
| AgglomerativeClustering_Avg  | 0.5384      | 8167.2413         | 0.6199         |

## Plots

### Elbow Plot

The elbow plot shows the distortion (sum of squared distances to the nearest cluster center) for different values of the number of clusters for the KMeans algorithm. The optimal number of clusters is usually at the 'elbow' of the plot, where the distortion starts to decrease more slowly.

![Elbow Plot](./figures/png/elbow.png)

### Dendrogram Plot

The dendrogram plot shows the hierarchical clustering of the data using the AgglomerativeClustering algorithm with Ward linkage. The x-axis shows the data points and the y-axis shows the distance between clusters. The horizontal lines represent the merging of two clusters. The optimal number of clusters can be determined by cutting the dendrogram at a specific height.

![Dendrogram Plot](./figures/png/dendrogram.png)

### KMeans

#### Cluster Plot

The cluster plot shows the geographical distribution of the clusters for the KMeans algorithm. Each color represents a different cluster.

![KMeans Cluster Plot](./figures/png/KMeans.png)

#### Cluster Counts Plot

The cluster counts plot shows the number of data points in each cluster for the KMeans algorithm.

![KMeans Cluster Counts Plot](./figures/png/KMeans_counts.png)

#### Cluster Pie Chart

The cluster pie chart shows the proportion of data points in each cluster for the KMeans algorithm.

![KMeans Cluster Pie Chart](./figures/png/KMeans_pie.png)

### AgglomerativeClustering_Ward

#### Cluster Plot

The cluster plot shows the geographical distribution of the clusters for the AgglomerativeClustering_Ward algorithm. Each color represents a different cluster.

![AgglomerativeClustering_Ward Cluster Plot](./figures/png/AgglomerativeClustering_Ward.png)

#### Cluster Counts Plot

The cluster counts plot shows the number of data points in each cluster for the AgglomerativeClustering_Ward algorithm.

![AgglomerativeClustering_Ward Cluster Counts Plot](./figures/png/AgglomerativeClustering_Ward_counts.png)

#### Cluster Pie Chart

The cluster pie chart shows the proportion of data points in each cluster for the AgglomerativeClustering_Ward algorithm.

![AgglomerativeClustering_Ward Cluster Pie Chart](./figures/png/AgglomerativeClustering_Ward_pie.png)

### AgglomerativeClustering_Average

#### Cluster Plot

The cluster plot shows the geographical distribution of the clusters for the AgglomerativeClustering_Average algorithm. Each color represents a different cluster.

![AgglomerativeClustering_Average Cluster Plot](./figures/png/AgglomerativeClustering_Average.png)

#### Cluster Counts Plot

The cluster counts plot shows the number of data points in each cluster for the AgglomerativeClustering_Average algorithm.

![AgglomerativeClustering_Average Cluster Counts Plot](./figures/png/AgglomerativeClustering_Average_counts.png)

#### Cluster Pie Chart

The cluster pie chart shows the proportion of data points in each cluster for the AgglomerativeClustering_Average algorithm.

![AgglomerativeClustering_Average Cluster Pie Chart](./figures/png/AgglomerativeClustering_Average_pie.png)

