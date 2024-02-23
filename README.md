# Machine-Learning-Project
### EDA for Chemical Descriptor Analysis
- Given a data with columns of chemical descriptors, my task is to perform EDA and dimensionality reduction technique to understand the data.
- Method used:
  1. Used **_Network Garph_** to find the highly correlated pair of descriptors
  2. Used **_Principal Component Analysis (PCA)_** to observe clusters, i.e. the data points that share underlying features. Also, I remove outliers based on the PCA output using Euclidean Distance
  3. Used **_t-SNE_** to further understand the data's structure. Small clusters observed.
  4. Employ **_ANOVA_** test to check if there are any statistically significant differences in the mean of the continuous target variable betweeen the categories of a nominal variable
 
### Clustering Analysis for chemical data
- The goal of this project is to familiarize with and understand the clustering techniques
- Method used:
  1. Performed **_K-mean Clustering_**: finding the optimal k using elbow method
  2. Used **_DBSCAN_** to get the clusters: finding the optimal epsilon using k-distance method
  3. Used **_t-SNE_** to visualize the k-mean clusters and DBSCAN clusters
  4. Using **_Cosine Distance_** as an alternate distance metric for k-mean clustering because the data is composed of binary values
 
### Binary Prediction
- My task is to predict the disease type (phenotype) from transcriptomics data. Disease: UCEC (uterine corpus endometrial carcinoma). Labels (0/1) are encoding tumor grade “II-” vs. “III+”
