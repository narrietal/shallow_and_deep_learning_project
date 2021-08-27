# README
Project developed for a Deep Learning course at the Sophia Antipolis, Université Côte D'Azur.

The repository contains 3 notebooks.

1. In the 1st notebook I experiment with the **feature detection algorithm SIFT** and feature matching techiques to achieve and Image Retrieval engine.

2. In the 2nd notebook I implement an image retrieval engine base on the **Bag Of Visual Words (BOVW)** approach. By applying **K-Means** on the descriptors we found new features which we turn into histograms and use a **feed forward fully-connected neural network** to classify the images. Finally in the last sections I compare this technique with a pre-trained **CNN** (using transfer learning techniques).

3. In the 3rd notebook I experiment with the German Traffic Sign Recognition Benchmark (GTSRB) dataset in order to apply some **data augmentation techniques**. First by changing the data itself, secondly by generating new data with the implementation of a **GAN**.
