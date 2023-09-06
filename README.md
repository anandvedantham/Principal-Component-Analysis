# Principal-Component-Analysis
Principal Component Analysis (PCA) is a dimensionality reduction technique widely used in data analysis and machine learning. It is a mathematical procedure that transforms high-dimensional data into a lower-dimensional form while preserving as much of the original variance as possible. PCA achieves this by identifying and extracting the principal components (PCs) from the data, which are linear combinations of the original features. These principal components are orthogonal (uncorrelated) and sorted by the amount of variance they explain, with the first PC explaining the most variance in the data.

Some of the benefits of PCA are:
- It can improve the performance and efficiency of machine learning models by reducing the computational complexity and avoiding overfitting.
- It can help to discover hidden patterns or structures in the data that are not obvious in the original features.
- It can help to remove noise or irrelevant information from the data by discarding the principal components with low variance.
  
### Implementation

Performing PCA and Clustering (Hierarchical and K-Means)

- Importing the required libraries and reading the dataset
- Data exploration
- Analizing the Principal Components
- Performing Hierarchical clustering on the data
- Performing K-Means clustering on the data
  
 ### Packages Used
 
- Pandas
- Numpy
- Matplotlib.pyplot
- Seaborn
- from sklearn.decomposition import PCA
- from sklearn.preprocessing import scale
