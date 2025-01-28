## **Online Retail Dataset Analysis with Unsupervised Learning**

![GitHub stars](https://img.shields.io/github/stars/Amitgm/Customer_segmentation_k_means_and_DBSCAN?style=social)
![License](https://img.shields.io/badge/license-MIT-blue)

This project demonstrates an in-depth analysis of the Online Retail Dataset using unsupervised learning techniques. The goal is to uncover meaningful insights and patterns within the dataset by applying various clustering algorithms, including K-Means, DBSCAN, and others.

#### **Key Features**
- **Exploratory Data Analysis (EDA):** A comprehensive exploration of the dataset to understand its structure, trends, and anomalies.
- **Clustering Techniques:** Implementation of popular unsupervised learning algorithms to group similar data points and identify hidden patterns.
  - **K-Means Clustering:** Partitioning data into distinct clusters based on similarity.
  - **DBSCAN (Density-Based Spatial Clustering):** Identifying clusters of varying shapes and handling noise in the dataset.
  - **Other Algorithms:** Additional clustering methods to compare and contrast results.
- **Visualizations:** Clear and insightful visual representations of the clusters and analysis results.
- **Insights:** Actionable conclusions drawn from the clustering process to better understand customer behavior, product segmentation, and more.

This notebook serves as a practical guide for applying unsupervised learning to real-world datasets, showcasing how clustering can be used to derive valuable business insights.
#### **Usage**
- To run the analysis, open the Google Colab notebook
- Download the zip file and upload it to your Google Colab notebook
- Run the Notebook

#### **Results**
- Identified 5 distinct customer segments using K-Means clustering.
- Detected outliers and noise in the dataset using DBSCAN.
- Visualized clusters using 2D and 3D plots.

#### **Below are the results of the 3d plot clustering of K-means and DBSCAN**


<div align="center">
    <img src="./images/download (4).png" alt="Clustering Results" width="500">
    <p><em>Figure 1: Clustering results using K-Means.</em></p>
</div>


<div align="center">
    <img src="./images/download (5).png" alt="Clustering Results" width="500">
    <p><em>Figure 2: Clustering results using DBSCAN</em></p>
</div>

#### **Using supervised learning these clusters are given as labels to the retail dataset**

<div align="center">
    <img src="./images/download (6).png" alt="Confusion Matrix" width="500">
    <p><em>Figure 3: Confusion Matrix of all the cluster.</em></p>
</div>
