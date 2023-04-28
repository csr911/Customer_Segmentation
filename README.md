# Customer_Segmentation

Table of Contents:

•	Introduction
o	Project Overview
o	Problem Statement and Objective
o	Model Development and Evaluation

•	Data Modeling
o	Import Packages

•	Segmentation
o	Data
o	Optimal number of clusters
o	Parameter Grid
o	K-Means
o	Hierarchical Clustering


Introduction:

The purpose of this dataset is to help us understand customer behavior and purchasing data in a supermarket mall through membership cards. The data includes basic information about customers such as their ID, age, gender, annual income, and spending score. Spending score is a parameter assigned to customers based on their purchasing behaviour. The goal of this dataset is to use unsupervised ML techniques, specifically K-Means clustering algorithm, to segment the customers into groups and identify the target customers who are likely to converge. By understanding the customers better, the mall can plan their marketing strategy accordingly and increase their revenue. This dataset is designed for learning purposes and serves as an excellent example of how to use unsupervised machine learning algorithms in practice.

Project Overview:

The aim of this project is to segment customers of a mall. I am using K-means clustering algorithm to cluster customers based on their features such as age, gender, annual income, and spending score.

Problem Statement and Objective:

The mall wants to understand the customer segments to better target marketing efforts and improve sales. The objective of this project is to identify distinct customer segments and provide recommendations to the marketing team to develop targeted marketing strategies.

Model Development and Evaluation:

K-means clustering algorithm was used to develop the model. The optimal number of clusters was selected using the elbow method and silhouette score. The model was evaluated using within-cluster sum of squares (WCSS) and silhouette score.
