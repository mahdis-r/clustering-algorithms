# clustering-algorithms
The notebook contains a project that implements various clustering algorithms and visualizes the results on different datasets. Here’s an overview of the contents:

## 1. Data Generation and Visualization:

- The notebook starts with creating sample datasets like blobs, circles, and moons using functions from `sklearn.datasets` such as `make_blobs` and `make_circles`.
- Data points are stored and plotted using `matplotlib` to provide a visual representation of the clusters.

  
  <img width="563" height="443" alt="image" src="https://github.com/user-attachments/assets/23cab216-cc67-43fa-af81-a11c09de1a88" />

  <img width="559" height="443" alt="image" src="https://github.com/user-attachments/assets/506d19c6-7fb0-4735-8892-7abd18a1b21d" />

  <img width="568" height="443" alt="image" src="https://github.com/user-attachments/assets/e408c0f8-bec3-48d5-bd87-c3f4dde048b1" />



  
## 2. Clustering Techniques:


- **K-Means Clustering:** Applied to the generated datasets, and the results are visualized with cluster centers.

  <img width="563" height="443" alt="image" src="https://github.com/user-attachments/assets/f01104e5-8a89-485f-9193-8987694fec18" />

  <img width="568" height="443" alt="image" src="https://github.com/user-attachments/assets/1f617c2f-6ddc-4138-a278-b25a3441678e" />

  <img width="559" height="443" alt="image" src="https://github.com/user-attachments/assets/c5e0c19e-3897-46a2-9c68-bd4cc0f6e546" />



- **Agglomerative Clustering:** Explored using hierarchical methods, with evaluations based on clustering performance metrics.

  <img width="563" height="443" alt="image" src="https://github.com/user-attachments/assets/d0620fc3-ad38-4ced-ac82-4bc638b0bcad" />

  <img width="568" height="443" alt="image" src="https://github.com/user-attachments/assets/c5889e65-86eb-4e8c-ab73-b811e8b1250e" />

  <img width="559" height="443" alt="image" src="https://github.com/user-attachments/assets/f53070c1-26b3-476b-b76c-01ca8ebee283" />



- **DBSCAN:** This density-based clustering technique is also applied, and similar performance metrics are evaluated.

  <img width="563" height="443" alt="image" src="https://github.com/user-attachments/assets/87ed76c5-2345-4dbe-b9e2-4967ea389a6b" />

  <img width="559" height="443" alt="image" src="https://github.com/user-attachments/assets/e8873ae5-a1da-44fd-9296-405ed62f7e38" />

  <img width="568" height="443" alt="image" src="https://github.com/user-attachments/assets/142bb130-196b-4b4c-8484-47c3b3ab7720" />



## 3. Evaluation Metrics:

- **Rand Index** and **Jaccard Index** are used to evaluate the clustering performance for each algorithm. These are standard metrics for comparing how well the predicted labels match the true labels.

  
## 4.Visualization of Results:

- The notebook includes scatter plots to display the clustering outcomes for each algorithm and dataset, with color-coding to represent different clusters.
