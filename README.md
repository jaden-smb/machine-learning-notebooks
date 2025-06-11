# Machine Learning Notebooks

A collection of Jupyter notebooks for data analysis and machine learning projects, showcasing various techniques from supervised and unsupervised learning.

## Notebooks

### [STUDIO-GENDER-VIDEO-GAMES.ipynb](STUDIO-GENDER-VIDEO-GAMES.ipynb)

This notebook analyzes gender representation in video games using a dataset from Kaggle. The analysis includes:

- Descriptive statistics on gender distribution among video game characters
- Visual analysis of gender representation across different game genres
- Examination of character sexualization patterns by gender
- Correlation analysis between gender representation and game ratings
- Machine learning models:
  - Regression models to predict game ratings based on gender representation
  - Classification models to predict character roles based on attributes

### [PCA_NMF_GMM.ipynb](PCA_NMF_GMM.ipynb) 

This notebook explores face recognition techniques using the Labeled Faces in the Wild (LFW) dataset with dimensionality reduction and clustering methods:

- **Principal Component Analysis (PCA)**: Linear dimensionality reduction to identify directions of maximum variance
- **Non-negative Matrix Factorization (NMF)**: Parts-based representation for decomposing data into non-negative components
- **Gaussian Mixture Models (GMM)**: Probabilistic clustering assuming data is generated from Gaussian distributions
- Comparison of these methods for facial recognition tasks
- Visualization of eigenfaces and component interpretations

### [UNSUPERVISED-METHODS.ipynb](UNSUPERVISED-METHODS.ipynb)

This notebook demonstrates the application of various unsupervised learning methods to analyze cybersecurity threat data:

- **K-Means Clustering**: For partitioning data into distinct groups
- **DBSCAN**: For density-based clustering and anomaly detection
- **Hierarchical Clustering**: For creating a hierarchical structure of clusters
- Analysis of a global cybersecurity threats dataset (2015-2024)
- Visualization of attack patterns, financial losses, and affected users

## Technologies Used

- **Python libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Data processing**: Data cleaning, preprocessing, normalization, and merging
- **Visualization**: Various chart types for exploratory data analysis and model interpretation
- **Machine Learning**: 
  - Supervised: Linear regression, Ridge regression, Decision trees, KNN
  - Unsupervised: PCA, NMF, GMM, K-Means, DBSCAN, Hierarchical clustering

## Dataset Sources

- Gender Representation in Video Games: [Kaggle dataset](https://www.kaggle.com/datasets/br33sa/gender-representation-in-video-games) by br33sa
- Global Cybersecurity Threats: [Kaggle dataset](https://www.kaggle.com/datasets/atharvasoundankar/global-cybersecurity-threats-2015-2024) by atharvasoundankar
- Labeled Faces in the Wild: Accessed via scikit-learn's `fetch_lfw_people()` function
