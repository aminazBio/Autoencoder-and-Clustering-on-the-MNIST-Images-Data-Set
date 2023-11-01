# Autoencoder-and-Clustering-on-the-MNIST-Images-Data-Set
The MNIST dataset is consists of a collection of handwritten digit images, where each image is a grayscale 28x28 pixel representation of a single digit ranging from 0 to 9.  
The dataset is split into two main parts:
A training set with 60,000 examples (which splitet to parts itself, 18,000 labeled 42,000 unlabeled) and a test set with 10,000 examples. The dataset’s ten classes correspond to the digits 0 to 9.  

An autoencoder is an unsupervised learning technique for neural networks that learns effcient data representations (encoding) by training the network to ignore signal noise.  

In this program, the clustering algorithm k-means, was applied to the unlabeled trainig set from the MNIST dataset and so it labeled them.  
Additionaly, the labeled data and labeled clusters were combined to create a new training dataset.
Also, the MLP classifier was implemented on primary and secondary training data and accuracy metrics and confusion matrix were employed for them.
