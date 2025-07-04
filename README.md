 K-Means Clustering on Mall Customers Dataset

##  Dataset
Path used: `C:\Users\anany\Downloads\archive\Mall_Customers.csv`

##  Objective
Perform customer segmentation using K-Means Clustering to discover spending/income patterns.

##  Workflow
1. Loaded dataset using Pandas.
2. Encoded gender to numerical format.
3. Standardized features using `StandardScaler`.
4. Used the Elbow Method to find optimal number of clusters (K=5).
5. Applied KMeans clustering.
6. Reduced dimensions with PCA and visualized clusters.
7. Evaluated clustering quality using Silhouette Score.

##  Output
- **Optimal K**: 5
- **Silhouette Score**: ~0.45
- **Visuals**: Elbow plot and 2D cluster scatter plot using PCA

##  Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- sklearn

##  Concepts Learned
- Unsupervised learning
- Clustering evaluation
- PCA for visualization
