# KNN-Classifier
the k-nearest neighbors  (k-NN) is a non-parametric method used for classification and regression.In both cases, the input consists of the k closest training examples in the feature space.

Program on python3 using pytorch library alone

KNN clssificaion on 'MNIST' and 'CIFAR10' dataset
ABOUT DATASETS
Uploaded 'MNIST' and 'CIFAR10' datasets in python file format.So one has to load those files. 
MNIST dataset contains 1000 training samples and 100 test samples.Each are gray scale images and 28x 28 size
Where as the CIFAR10 contains 1000 train and 100 test samples with color channels of size 28x28

K-Nearest neighbour classifier:The classifier which classifies based on the nearest 

###ABOUT THE PROGRAM 
ON MNIST
KNN Classifier:Here the classification is based on euclidean distance as metric and intensity itself is the feature vector.
Classification have been done for K=1,3 and 5.For K=3 and 5 majority label is assigned to test label.Neglected the case of all different label.
ON CIFAR10

KNN Classifier:Here the classification is based on euclidean distance as metric and Histogram of three channels forms the feature vector.
Classification have been done for K=1,3 and 5.For K=3 and 5 majority label is assigned to test label.Neglected the case of all different label.
