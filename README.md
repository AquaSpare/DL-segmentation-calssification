# deep_learning_assignment_3
Deep learning based image segmentation and classification

This repository contains the pytorch code used for a the final project in the course Deep Learning in Image Analysis

1. First problem is about classification of hand-written digits using a convolutional neural network on the MNIST dataset, several models are evaluated

2. Second problem is in semantic segmentation of biomedical images using a UNET model architecture on the WARWICK dataset

Information about the MNIST dataset: The MNIST dataset consists of 60000 training images, and 10000 test images. The dataset has become a classic benchmark dataset for machine learning; do checkout the http://yann.lecun.com/exdb/mnist/ page for some context. All images are 28x28 pixels and stored in the png-file format.

Information about the WARWICK dataset: The WARWICK dataset consists of 85 training images, and 60 test images, each of size 128×128 and with a binary mask indicating Glandular regions in the images. This is a selected and pre-processed part (colors are unmixed and images are resized) of the Warwick-QU dataset (released with the MICCAI’2015 GlaS contest). See https://warwick.ac.uk/fac/sci/dcs/research/tia/glascontest/download/ for information about the original data.
