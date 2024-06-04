• Accomplished an 88.88% accuracy rate in categorizing 4 different bird species (grey partridge, stock dove, turtle dove, yellowhammer) by developing and optimizing a Convolutional Neural Network (CNN) model architecture with 3 convolutional layers, a max pooling layer, 2 fully connected layers, dropout, and appropriate hyperparameter tuning on a dataset of bird song spectrograms.

• Achieved a 93% accuracy rate for correctly classifying the Turtledove species by conducting an in-depth confusion matrix analysis to identify it as the best performing species compared to the other 3 species.

• Led the unsupervised clustering analysis by applying the k-means algorithm on scaled data after testing 4 data processing techniques (scaling, PCA, winsorizing, log-transform), resulting in the identification of 4 clear and compact clusters representing each of the 4 bird species.

• Directed a robust outlier detection analysis by calculating the Euclidean distance between each data point and assigned centroid, setting a 95th percentile threshold distance, and discovering the Turtledove species had the lowest outlier count, indicating tighter within-cluster grouping.

• Evaluated the relative compactness of clusters for each species by comparing their within-cluster sum of squares (WSS) scores, a clustering performance metric, and discovering the Turtledove clusters had the lowest WSS, meaning its data points grouped most tightly and effectively together.

• Improved the model's ability to generalize to new, unseen data by reducing overfitting through techniques like expanding the dropout rate, increasing the weight decay term, expanding the training data size, and adding more convolutional layers, leading to stabilized and reduced gap between training and
