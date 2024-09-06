# clustering-algorithms
The notebook contains a project that implements various clustering algorithms and visualizes the results on different datasets. Here’s an overview of the contents:

## 1. Data Generation and Visualization:

- The notebook starts with creating sample datasets like blobs, circles, and moons using functions from `sklearn.datasets` such as `make_blobs` and `make_circles`.
- Data points are stored and plotted using `matplotlib` to provide a visual representation of the clusters.
  
## 2. Clustering Techniques:

- **K-Means Clustering:** Applied to the generated datasets, and the results are visualized with cluster centers.
- **Agglomerative Clustering:** Explored using hierarchical methods, with evaluations based on clustering performance metrics.
- **DBSCAN:** This density-based clustering technique is also applied, and similar performance metrics are evaluated.
  
## 3. Evaluation Metrics:

- **Rand Index** and **Jaccard Index** are used to evaluate the clustering performance for each algorithm. These are standard metrics for comparing how well the predicted labels match the true labels.
  
## 4.Visualization of Results:

- The notebook includes scatter plots to display the clustering outcomes for each algorithm and dataset, with color-coding to represent different clusters.
