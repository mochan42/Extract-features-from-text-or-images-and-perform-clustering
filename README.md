# Extract-features-from-text-or-images-and-perform-clustering.

* The aim of the project is to perform unsupervised classification (clustering) of objects from the daily life based on a text description of these objects or on their images.<br>
* For the clustering based on text description, a number of NLP models are used to extract features, then a dimension reduction is performed via a PCA and a clustering is eventually performed.<br>
* For the clustring based on images, SIFT and VGG16 are used. Then a dimension reduction is performed via a PCA and a clustering is eventually performed.<br>
* The ARI is calculated for each technique and it appears that using VGG16 provides the best ARI score to create a classifier for these objects.
