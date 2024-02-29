# Machine-Learning-Projects
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
 
### Linear Model
- My task is to predict the disease type (phenotype) from transcriptomics data, focusing on UCEC (uterine corpus endometrial carcinoma) with labels (0/1) encoding tumor grade “II-” vs. “III+”.
- Perform **binary classification** using **_linear models_** and measure classification performance with accuracy and F1-score on the test set.
- Develop a pipeline to experiment with various linear models, including **_linear regression, logistic regression, ridge regression, and LASSO_**.
- Regularize parameters to enhance model performance.
- Conduct **feature selection** using **_Random Forest_** and **_Chi-square Test_**.
- Visualized the dataset using **_T-SNE_** and **_PCA_** techniques.
- Got 91.6% F1-score.

### Binary Classification
- The goal is to Predict the binarized brightness level for classification into high brightness (class 1) and low brightness (class 0) among mutants of Green Fluorescent Protein.
- Load descriptors as new columns to train the model.
- Select a set of descriptors strategically to achieve the highest prediction accuracy.
- Choose the optimal training model and optimize its parameters through _**parameter tuning**_.
- Perform feature selection using **_Recursive Feature Elimination (RFE)_**
  
### Regression Model
- Goal is to predict quantitative measurements of the band gap (Egap) for a set of inorganic crystalline materials
- Execute a model pipeline and determine that **_xgboost_** outperforms other models.
- Implement **_model stacking_** techniques to combine predictions from multiple models.
- Conduct fine parameter tuning by setting adjustments.
