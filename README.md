🛍️ Mall Customer Segmentation using K-Means Clustering
🎯 Objective
This project applies unsupervised machine learning using K-Means Clustering to segment mall customers based on their purchasing behavior and demographics. The goal is to identify distinct customer groups for targeted marketing strategies.

🧰 Tools & Technologies
Python

Pandas & NumPy – for data manipulation

Matplotlib & Seaborn – for visualizations

Scikit-learn – for clustering, evaluation metrics, and PCA

📁 Dataset
The dataset includes customer attributes such as:

Customer ID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

Make sure to include Mall_Customers.csv in your repository for reproducibility.

🔍 Workflow Overview
1. Load and Visualize Dataset
The dataset is explored for data types, null values, and descriptive statistics.

Initial visualizations are created to understand customer distribution.

2. Apply PCA (Optional)
Dimensionality reduction with PCA is used to convert features to 2D for visualizing clusters more clearly.

3. Fit K-Means and Predict Clusters
K-Means clustering is applied to segment customers.

Cluster labels are added to the dataset for analysis and plotting.

4. Elbow Method to Find Optimal K
The Elbow Method is used to determine the optimal number of clusters by evaluating the within-cluster sum of squares (WCSS).

5. Cluster Visualization
Customers are visualized in 2D space (using PCA if needed), with color-coded clusters to reveal patterns.

6. Evaluate with Silhouette Score
Silhouette Score is used to measure the quality of clusters and assess the separation between them.

📈 Key Insights
Cluster analysis reveals patterns like high-income low-spenders or young high-spending groups.

Businesses can use these segments to tailor promotions and services effectively.
