# Clustering-Projects

# Clustering Projects - McDonald's Case Study Conversion from R to Python

# Overview
This repository contains the Python code for converting McDonald's Market Segmentation Case Study from R to Python. The goal of this project was to replicate the R-based clustering analysis and visualization techniques in Python using pandas, scikit-learn, matplotlib, seaborn, and other Python libraries.

The case study applies k-means clustering on customer data to segment customers based on their preferences and demographic data. Additionally, it includes evaluations of cluster stability, segment profiling using decision trees, and visualizations of the results.

# Project Details
# Data Preprocessing
Load the data: The dataset is loaded from a CSV file using pandas.
Categorical Encoding: Binary encoding is applied to the categorical features ("Yes" and "No") to convert them into numeric values (1 and 0).

# Clustering Analysis
K-Means Clustering: The KMeans algorithm from scikit-learn is applied to segment the customers into clusters. The optimal number of clusters is determined using the "elbow method" based on the WCSS (Within-Cluster Sum of Squares).
Silhouette Score: Stability of the segments is evaluated by calculating silhouette scores.

# Decision Tree Analysis
Segment Profiling: A decision tree classifier is applied to profile and interpret the features influencing each customer segment.

# Visualizations
Cluster Visualization: Various plots (e.g., scree plot, silhouette scores, mosaic plots) are created to visualize the clustering results and evaluate the segment stability.

# Google Colab Integration
The full code for exploiting and visualizing the data in a Google Colab notebook is provided here: Google Colab - Clustering Project
link: https://colab.research.google.com/gist/BadakalaYashwanth/ad062eeb212334fda1046e6a91a1cf61/clustering-project.ipynb

# Technologies Used
Python Libraries:
pandas: Data manipulation and analysis.
numpy: Numerical operations.
scikit-learn: Machine learning and clustering algorithms.
matplotlib, seaborn: Data visualization.
statsmodels: Advanced statistical models (used for mosaic plots).

# Tools:
Google Colab: Cloud-based Python notebook used for data exploration and visualization.
