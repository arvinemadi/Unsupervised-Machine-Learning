## Examples of Unsupervised Machine Learning

### Dimension reduction using PCA and tSNE

Data from https://www.kaggle.com/competitions/digit-recognizer/data
PCA implement by 1- calculating covariance matrix 2- using sklearn
tSNE using sklearn

### Variational Auto Encoder.
Variational Auto-Encoder on MNIST data using pytorch. Many examples and explanation on this but I could not find a reference that explains how the loss function is created. This lecture is very useful [Yotube](https://www.youtube.com/watch?v=uaaqyVS9-rM) but there also the derivation of the loss function is not done but general concept is explained in detail. The same data as above is used.

### K-means application in unsupervised and semisupervised learning.
Three application of K-means are tried.
- It is used on Olivetti faces dataset for classification [Link](https://scikit-learn.org/0.19/datasets/olivetti_faces.html). 
- It is used as a non-linear dimension reduction
- It is used to label a dataset.

The notebook shows some comments and discussed the limitations.
