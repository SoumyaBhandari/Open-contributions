# Dimensionality Reduction
The number of input variables or features for a dataset is referred to as its dimensionality.
Dimensionality reduction refers to techniques that reduce the number of input variables in a dataset.
More input features often make a predictive modeling task more challenging to model, more generally referred to as the curse of dimensionality.
High-dimensionality statistics and dimensionality reduction techniques are often used for data visualization. Nevertheless these techniques can be used in applied machine learning to simplify a classification or regression dataset in order to better fit a predictive model.

Large numbers of input features can cause poor performance for machine learning algorithms.
Dimensionality reduction is a general field of study concerned with reducing the number of input features.
Dimensionality reduction methods include feature selection, linear algebra methods, projection methods, and autoencoders.

## t-distributed Stochastic Neighbor Embedding (t-SNE)
This technique reduces the n numeric columns in the dataset to fewer dimensions m (m < n) based on nonlinear local relationships among the data points. 
Specifically, it models each high-dimensional object by a two- or three-dimensional point 
in such a way that similar objects are modeled by nearby points and dissimilar objects are modeled by distant points in the new lower dimensional space.

## Principal Component Analysis (PCA)
Principal component analysis (PCA) is a statistical procedure that orthogonally transforms the original n numeric 
dimensions of a dataset into a new set of n dimensions called principal components. As a result of the transformation,
the first principal component has the largest possible variance; each succeeding principal component has the highest possible variance under the constraint that
it is orthogonal to (i.e., uncorrelated with) the preceding principal components. Keeping only the first m < n principal components reduces the data dimensionality 
while retaining most of the data information, i.e., variation in the data. Notice that the PCA transformation is sensitive to the relative scaling of the original columns, 
and therefore, the data need to be normalized before applying PCA. Also notice that the new coordinates (PCs) are not real, system-produced variables anymore. 
Applying PCA to your dataset loses its interpretability.If interpretability of the results is important for your analysis, PCA is not the transformation that you should apply.

