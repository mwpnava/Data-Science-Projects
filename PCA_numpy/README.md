## Principal Component Analysis with numpy functions :

### About this project:

In this project, I will apply PCA to a dataset without using any of the popular machine learning libraries such as scikit-learn and statsmodels. The goal of this document is to have a deeper understanding of the PCA fundamentals using functions just from numpy library.

### Dataset

Dataset: This is perhaps the best known database to be found in the pattern recognition literature. Fisher's paper is a classic in the field and is referenced frequently to this day. The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other.

Retrieved from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data


### Tech:

- Python 3
- numpy
  - np.cov()
  - np.linalg.eig(covariance_matrix)
  - np.linalg.svd(X.T) (it is an alternative to get eigenvalues and eigenvectors)
  - np.cumsum()
  - np.dot()
- pandas
- matplotlib
- seaborn

### Author
[Wendy Navarrete](http://wendynavarrete.com)
