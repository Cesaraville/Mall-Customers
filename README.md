## Mall-Customers
# An unsupervised machine learning to segment mall customers into distinct groups based on their demographics and purchasing behavior. The goal is to identify key customer profiles that can inform targeted marketing strategies.
## Model: Unsupervised Learning Model
## Dataset: Mall Customer Segmentation Data
## Preprocessing
# One-hot encoded categorical variables
# Scaled numerical features using MinMaxScaler and StandardScaler
# Applied PCA and t-SNE for visualization
## Evaluation: KMeans
# Silhouette Score: 0.591665871638838
# Davies Bouldin Score: 0.4846581131074428
# Calinsku Harabasz Score: 1420.9895912666316
## Objective:
# To group customers into meaningful segments using K-Means Clustering, and interpret those clusters to help the business:
  # Identify high-value customer groups
  # Develop personalized marketing strategies
  # Improve customer retention and satisfaction
