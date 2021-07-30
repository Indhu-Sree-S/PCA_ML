# PCA_ML

Problem Statement:

Conducting the Principal Component Analysis for the Retail Sale data.

Problem Description:

Preprocess the data and then the scaled data are passed through various tests such as the Bartlett’s test of sphericity and the KMO test to determine whether the dimensionality reduction techniques such as the PCA can be applied on this dataset.

Inference:

The Bartlett test show that the hypothesis of the correlation present among the features. For our dataset the p_value is 0.0 with 95% confidence. The KMO test can be used to determine the sampling adequacy. The KMO score of 0.461 indicates that the dataset satisfies the sampling adequacy. So, principal component analysis can be done on the dataset. 

The scree plot shows the effect on variance with increase in number of principal components. The optimal number of components is 6 as the variance drops below 1 after 6 components

The weight of the variables in the principal components can be obtained from the components table. Eigen value is the amount of variance of observed variables explained by the principal components. It can be seen that the 19% of the common variance is explained by the Principal Component 1. The 6 PCs cumulatively explain about 71% of the variance due the correlation among the observed variables and errors. 

Conclusion:

Thus, principal factor analysis has helped us reducing the dimensions by introducing principal components where each principal component has helped in explaining the underlying unobserved variance due to the correlation among the variables and the error. Principal Component Analysis is conducted for the retail sale data.
