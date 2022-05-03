# Principal Component Analysis (PCA)  
Principal Component Analysis (PCA) is used in exploratory data analysis and for multidimensionality reduction. The main idea is to project data points onto only the first few principal components to obtain lower-dimensional data while preserving as much of the data’s variation as possible. In other words, using PCA we remove the redundant and highly-correlated data and we keep only the most significant data features for further analysis.  

The first principal component is defined as a direction that maximizes variance of the projected data, the second principal component is a direction orthogonal to the first principal component that is the next one to maximize the variance, etc. It can be proved that the principal components are the eigenvectors of the covariance matrix and are computed either by eigendecomposition of the covariance matrix or by the SVD of the data matrix.  

![alt](https://www.researchgate.net/profile/Raphael-Pelissier/publication/284160710/figure/fig2/AS:298853849944064@1448263718024/Principal-Component-Analysis-PCA-based-on-20-descriptive-variables-used-for.png)
## Datasets
- Palmer pegnguins dataset  
Dataset contains data for 344 penguins. There are 3 different species of penguins in this dataset, collected from 3 islands in the Palmer Archipelago, Antarctica. Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network.  
- sklearn.datasets.load_wine  
The wine dataset is a classic and very easy multi-class classification dataset.  
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html
## Packages
* matplotlib
* numpy
* pandas
* seaborn
