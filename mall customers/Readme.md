Task 12: KMeans – Customer Segmentation
 Objective

The goal of this task is to perform customer segmentation using the KMeans clustering algorithm.
Customers are grouped based on their Annual Income and Spending Score to help businesses understand customer behavior and design targeted marketing strategies.

 Tools & Technologies Used

Python

Pandas – Data handling

Scikit-learn – KMeans & StandardScaler

Matplotlib & Seaborn – Data visualization

 Dataset

Dataset Name: Mall Customer Segmentation Dataset

Source: Kaggle

Key Features Used:

Annual Income (k$)

Spending Score (1-100)

The dataset represents customer information collected from a shopping mall.

Steps Performed

Dataset Preparation

Loaded customer data into a Pandas DataFrame.

Selected relevant features for clustering.

Feature Scaling

Applied StandardScaler to normalize the data.

Scaling ensures fair distance calculation in KMeans.

Elbow Method

Trained KMeans for different values of K (1–10).

Calculated inertia for each K.

Plotted the Elbow Curve to find the optimal number of clusters.

Model Training

Trained KMeans with the optimal number of clusters (K = 5).

Cluster Assignment

Assigned cluster labels to each customer.

Added cluster labels back to the dataset.

Visualization

Visualized clusters using a scatter plot.

Each cluster represents a distinct customer group.

Output

Saved the segmented dataset as segmented_customers.csv.

 Results

Successfully segmented customers into 5 distinct clusters.

Identified customer groups such as:

High income – High spending

High income – Low spending

Low income – High spending

Low income – Low spending

These insights can help businesses improve marketing and customer engagement.