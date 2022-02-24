# Clients_segmentation

Starting from the Online Retail dataset of UCI Machine Learning, we perform a segmentation of customers with various types of algorithms and data processing. 

In Clustering_transform we make an analysis of the different types of data treatments and look for the optimal number of clusters for various models, relying on a dendrogram, the elbow method and silhouette score.

In Clustering_standard we perform the same analysis but using only StandarScaler. 

In both case we conclude that there are three types of clients with the same means in number of invoices, Amount and days after last purchase. Also we use the same algorithm (kmeans) because it's seems to be less overlap between cases.

Classes with StandarScaler data and kmeans 
![image](https://user-images.githubusercontent.com/96470129/155516636-13d02d3f-c479-435b-8810-9b03d4b871ed.png)

Classes with Yeo-johnson, cbrt transforms and kmeans

![image](https://user-images.githubusercontent.com/96470129/155516888-7ef424f6-7602-4c66-9fe9-84cb64d155fd.png)



