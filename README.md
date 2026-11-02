# Customer Segmentation Using K-Means Clustering

## Week 3 Project: Unsupervised Learning and Clustering Analysis

This project applies K-Means clustering, an unsupervised machine learning algorithm, to segment customers based on their annual income and spending behaviour.

The analysis uses the Mall Customer Segmentation dataset and explores how clustering can help identify customer groups for targeted marketing strategies.

## Project Objectives

- Explore and understand the customer dataset.
- Perform data inspection and preprocessing.
- Apply K-Means clustering to identify customer segments.
- Determine the optimal number of clusters using the Elbow Method and Silhouette Score.
- Visualize and interpret customer groups.
- Discuss business applications and model limitations.

## Dataset

**Source:** [Mall Customer Segmentation Dataset on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

The dataset contains 200 customer records and five attributes:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

No missing values or duplicate records were identified.

## Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

1. Data loading and exploratory data analysis.
2. Data inspection and preprocessing.
3. Feature selection using Annual Income and Spending Score.
4. Feature standardization using StandardScaler.
5. Selection of cluster count using the Elbow Method and Silhouette Score.
6. Application of K-Means clustering.
7. Cluster visualization and customer profile interpretation.

## Model Results

The final K-Means model used **5 clusters** and achieved a silhouette score of **0.5547**.

| Cluster | Customers | Average Income (k$) | Average Spending Score |
|---|---:|---:|---:|
| 0 | 81 | 55.30 | 49.52 |
| 1 | 39 | 86.54 | 82.13 |
| 2 | 22 | 25.73 | 
