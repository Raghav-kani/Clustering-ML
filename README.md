# Clustering - ML

## 1.1 PROJECT SCOPE

The objective of this study is to do an unsupervised clustering of data on customer records taken from a database of a grocery store. 
Customer segmentation is the process of grouping consumers according to characteristics that are shared by all of the customers in a cluster. 

To maximise the value of each client to the firm, we will segment our customer base. 
To alter products in response to specific demands and consumer behaviour. 
The ability to address the needs of various clientele also benefits the firm.



## 1.2 BRIEF DISCUSSION

Importing the necessary libraries, and data viewpoint for better comprehension.

### Data Cleaning

By clearing pointless values, the data set is cleaned. Locating the data's Enrolled date. 
Adding a feature ("Customer For") that tracks how many days the customers have been making purchases in the store since the last date that was logged.

### Feature Engineering

Extracting new columns from old ones for clustering. 
There are a few outliers in the Income and Age aspects of the data that we have shown. The data's outliers will be eliminated.

### Data Pre-processing 

In data pre-processing, we Label encoding the categorical features and scaling the features using the standard scaler and creating a subset data frame for dimensionality reduction.

### Dimensionality Reduction

By choosing a set of primary variables, dimensionality reduction is the process of reducing the number of random variables being taken into account. 
A method known as PCA may be used to reduce the dimensionality of such a dataset, improving interpretability while minimising information loss.

### Clustering

While the characteristics have been condensed to three dimensions, agglomerative clustering will be used to do the clustering. 
A hierarchical clustering technique is agglomerative clustering. 
Up until the appropriate number of clusters is reached, samples are merged. 
The phases include the Elbow Method to estimate the number of clusters to create, Agglomerative Clustering for Clustering, and Scatter Plot Analysis for Cluster Analysis.

### Evaluating Model

Scatterplot is used to view the cluster profile based on income and spending. 
Visualization is done to view the cluster distribution. 
We can by using the plot. We can see that cluster 1 is our largest group of consumers, followed by cluster 0 in terms of size. 
For the focused marketing techniques, we might investigate the expenses made by each cluster.

### Profiling 

When profiling, we use Jointplot to cluster the data and visualize each column with a maximum of four clusters. 
We developed four clusters and utilized them to profile clients in clusters based on their family configurations, income levels, and spending habits.



## 1.3 PROJECT GOAL

The project's goal is to carry out unsupervised clustering. 
Dimensionality reduction and agglomerative clustering were both used. 
We utilize 4 clusters and deployed them to profile clients in clusters based on their family configurations, income levels, and spending habits. 
This may be applied while creating more effective marketing plans.
