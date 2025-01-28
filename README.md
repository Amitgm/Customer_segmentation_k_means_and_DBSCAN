## **Online Retail Dataset Analysis with Unsupervised Learning**

This project demonstrates an in-depth analysis of the Online Retail Dataset using unsupervised learning techniques. The goal is to uncover meaningful insights and patterns within the dataset by applying various clustering algorithms, including K-Means, DBSCAN, and others.

#### **Key Features**
- **Exploratory Data Analysis (EDA):** A comprehensive exploration of the dataset to understand its structure, trends, and anomalies.
- **Clustering Techniques:** Implementation of popular unsupervised learning algorithms to group similar data points and identify hidden patterns.
  - **K-Means Clustering:** Partitioning data into distinct clusters based on similarity.
  - **DBSCAN (Density-Based Spatial Clustering):** Identifying clusters of varying shapes and handling noise in the dataset.
  - **Other Algorithms:** Additional clustering methods to compare and contrast results.
- **Visualizations:** Clear and insightful visual representations of the clusters and analysis results.
- **Insights:** Actionable conclusions drawn from the clustering process to better understand customer behavior, product segmentation, and more.

#### **Methodology**
- **Data Preprocessing:**
- The dataset is cleaned, missing values are handled, and relevant features are extracted for analysis.
- **Clustering Implementation:**
  - **K-Means:** Clustering: Applied to partition customers into 5 distinct segments based on their RFM characteristics.
  - **DBSCAN:** Utilized to detect outliers and noise, providing a more nuanced understanding of the data distribution.
- **Model Evaluation:**
- The CatBoost algorithm is employed to classify data points based on the cluster labels. The model achieves high accuracy and F1 scores, as evidenced by the confusion matrix.
- **Visualization:**
- The clustering results are visualized using 2D and 3D plots, showcasing the formation of clusters and the distribution of data points.

#### **Results**
- Identified 5 distinct customer segments using K-Means clustering.
- Detected outliers and noise in the dataset using DBSCAN.
- Visualized clusters using 2D and 3D plots.
- Here Three features are taken Recency, Frequncy and Monetary value and their respective clusters are plotted to see their cluster formation.
- Catboost Algorithm is used to classify the points based on the cluster labels. As seen the F1 score and Accuracy is very high from the confusion matrix

### <div align="center"> **3d plot clustering of K-means and DBSCAN** </div>

<div align="center">
    <img src="./images/download (4).png" alt="Clustering Results" width="500">
    <p><em>Figure 1: Clustering results using K-Means.</em></p>
</div>


<div align="center">
    <img src="./images/download (5).png" alt="Clustering Results" width="500">
    <p><em>Figure 2: Clustering results using DBSCAN</em></p>
</div>

### <div align="center"> **Confusion Matrix of clusters** </div>

<div align="center">
    <img src="./images/download (6).png" alt="Confusion Matrix" width="500">
    <p><em>Figure 3: Confusion Matrix of all the cluster.</em></p>
</div>
