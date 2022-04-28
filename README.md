# Dimensionality-Reduction

**This technique is about taking your full dataset and reducing it to only the parts that hold the most information.**

## Dimensionality Reduction through Feature Selection and Feature Extraction
With large datasets, we often suffer from what is known as the "curse of dimensionality," and need to reduce the number of features to effectively develop a model. Feature Selection and Feature Extraction are two general approaches for reducing dimensionality.

## Feature Extraction using PCA
Principal Component Analysis is a common method for extracting new "latent features" from our dataset, based on existing features.
Note: Latent features are features that aren't explicitly in your dataset.

## Feature Extraction using random projection
Random Projection is computationally more efficient than PCA.

The random projection takes a dataset and transforms it into one with much smaller features.

There is a scenario where you may want to use Random Project and not PCA: When working with so many dimensions that PCA's performance becomes unacceptable for the situation. Random Projection indeed delivers higher performance than PCA especially in higher dimensional data -- with a decrease in quality of projection, however.

Note: the number of components is optional and can be computed by the algorithm.
