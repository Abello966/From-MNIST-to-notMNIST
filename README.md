# From MNIST to notMNIST
Transfer Learning study with Lasagne
The idea is to train a CNN on the MNIST dataset and use it as a feature extractor on the notMNIST dataset
With a standard CNN I got 95% test accuracy on MNIST that lead to 90% test accuracy on notMNIST using extracted features and logistic regression


# Requirements
Numpy, Theano, Lasagne, Sklearn, gzip, pickle

The MNIST dataset is automatically downloaded by a helper function

To execute the notMNIST part you need to download the notMNIST pickle, available here:

https://www.dropbox.com/s/1n48cxc8ex5ut8i/notMNIST.zip?dl=0
