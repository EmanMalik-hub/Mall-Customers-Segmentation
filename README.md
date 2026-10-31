Mall Customers Segmentation Using K-Means Clustering

Project Overview

This project focuses on customer segmentation using the K-Means Clustering algorithm. The goal is to group mall customers based on their annual income and spending score to identify different customer segments.

Customer segmentation helps businesses understand customer behavior and develop more targeted marketing strategies.

Dataset

The project uses the Mall Customers dataset, which contains 200 customer records and the following features:

CustomerID – Unique customer identifier

Gender – Customer gender

Age – Customer age

Annual Income (k$) – Annual income in thousands of dollars

Spending Score (1-100) – Spending score assigned to each customer

Note: CustomerID is excluded from clustering because it is an identification field, not a meaningful clustering feature.

Technologies & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

Project Workflow

Data loading and exploration

Exploratory Data Analysis (EDA)

Missing values and duplicate checking

Data visualization

Feature selection

Feature scaling using StandardScaler

Optimal cluster selection using the Elbow Method

Cluster evaluation using Silhouette Score

Customer segmentation using K-Means

Cluster visualization and interpretation

Model Selection

The Elbow Method and Silhouette Score were used to evaluate different values of K.

Based on the analysis, K = 5 was selected as a reasonable number of clusters for this project.

Results

The K-Means model divides customers into five clusters based on annual income and spending score.

These segments can help identify customer groups such as:

High-income, high-spending customers

High-income, low-spending customers

Low-income, high-spending customers

Low-income, low-spending customers

Customers with moderate income and spending patterns

How to Run

Download or clone this repository.

Open the Jupyter Notebook in Google Colab or Jupyter Notebook.

Upload the Mall Customers CSV dataset when prompted.

Run the notebook cells in order.

Learning Outcomes

Through this project, I practiced:

Unsupervised Machine Learning

K-Means Clustering

Exploratory Data Analysis

Feature Scaling

Elbow Method

Silhouette Score

Data Visualization

Future Improvements

Compare K-Means with other clustering algorithms.

Perform deeper customer segment analysis.

Explore additional customer features.

Develop business recommendations based on cluster profiles.
