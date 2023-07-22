# unsup-homework

# Unsupervised machine learning homework 
## Read the data using read csv function, checked and cleaned the data frame to make sure there were no issues with the data.
### Then ploted the data to show the elbow curve of the clusters in order to find what the correct number of clusters would be.
![elbow curve](Photos/bokeh_plot.png)
### Then I created a model using Kmeans to implement the amount of clusters I thought would be correct
![Kmeans](Photos/Kmeans.jpg)

### Then I plotted the Kmeans Data 
![Kmeansplot](Photos/coin_clusters_plot.png)

## Optimize Clusters with Principal Component Analysis is the next step
![pca](Photos/PCA.jpg)

### With that optimization I found going through the proccess lead to less steps with similar accuracy and results.

# This is the elbow of the PCA data
![pca_elbow](Photos/pca_elbow.png)

# This is the cluster of PCA data
![pca_cluster](Photos/pca_clusters.png)

## In conclusion after running the Kmeans model with the PCA data and the orginal data the PCA model allows for less time between processing, it achevied the same result in less steps.