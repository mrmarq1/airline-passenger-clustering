# Airline Passenger Clustering
Model to help identify segments from airline passenger data. To apply several clustering technqiues to data to assess optimal approach and determine keys segments.

## Project Motivation
- To practice and compare the performance of an array of clustering techniques.
- Gain experience using SilhouetteVisualizer to guide the determination of optimal cluster number.
- To practice analysing and generating descriptions of identified clusters.  

## Learning Points
- Accounting for the uniformity of cluster size as well as the silhouette score when interpreting SilhouetteVisualizer.
- How to determine hyperparameters for the DBScan algorithm.
- How to evaluate relationship bvetween identified clusters and features for desriptive analysis.

## Project Breakdown

### Data cleaning
- Conducted analyses to understand the dataset and clean it, handling outliers, dropping redundant features and stanardising it in the process.
- Applied PCA to reduce feature space and eliminate multicollinearity.

### Modelling
- Applied KNN clustering using the elbow technqiue and silhouette plotting to determine the optimal cluster number.
- Comapred KNN with DBSCAN, Gaussian Mixture Model and Mean Shift approaches.

### Plotting and analysis
- Analysed best performing model to determine breakdown of segments.
