Overview

This project explores clustering techniques to analyze an unlabeled dataset of 1000 data points with two features. Since the number of clusters is unknown, a model-based approach is used to determine the optimal clustering.

Dataset

Filename: cluster2.csv

Size: 1000 data points

Features: 2 (unnamed numerical variables)

Objective

Use either K-Means or Gaussian Mixture Models (GMM) to find clusters in the data.

Determine the optimal number of clusters using appropriate methodologies.

Visualize the clustering results.

Methodology

Preprocessing: Load and explore the dataset, checking for missing values and normalizing the data if necessary.

Choosing the Clustering Algorithm: Compare K-Means and GMM to select the best approach.

Determining Optimal Clusters:

Elbow Method: Analyze inertia values for K-Means.

Silhouette Score: Evaluate cluster separation.

Bayesian Information Criterion (BIC) & Akaike Information Criterion (AIC): Evaluate model complexity for GMM.

Final Model Training: Train the chosen model and apply clustering.

Visualization: Plot clusters using scatter plots.

Evaluation & Insights: Interpret clustering results and discuss findings.

Results: Refer to the results file

Technologies Used:

Python

Scikit-learn

Matplotlib & Seaborn

Pandas & NumPy


Future Improvements

Try alternative clustering methods such as DBSCAN.

Apply feature engineering to improve clustering quality.

Use real-world datasets for application-based clustering.

References

Course lectures on unsupervised learning.

Scikit-learn documentation.

