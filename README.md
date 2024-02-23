# Machine-Learning-Project
### Chemical Descriptor Analysis
- Given a data with columns of chemical descriptors, my task is to perform EDA and dimensionality reduction technique to understand the data.
- Method used:
  1. Used **_Network Garph_** to find the highly correlated pair of descriptors
  2. Used **_Principal Component Analysis (PCA)_** to observe clusters, i.e. the data points that share underlying features. Also, I remove outliers based on the PCA output using Euclidean Distance
  3. Used **_t-SNE_** to further understand the data's structure. Small clusters observed.
  4. Employ **_ANOVA_** test to check if there are any statistically significant differences in the mean of the continuous target variable betweeen the categories of a nominal variable
 
