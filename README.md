# AutoEmbedder
A semi-supervised DNN embedding system for clustering
-----------

This is the implementation of the AutoEmbedder. A jupyter notebook version and a python version is attached in the repo.

## Abstract
-----------

Clustering is widely used in unsupervised learning method that deals with unlabeled data. Deep clustering has become a popular study area that relates clustering with Deep Neural Network (DNN) architecture. Deep clustering method downsamples high dimensional data, which may also relate clustering loss. Deep clustering is also introduced in semi-supervised learning (SSL). Most SSL methods depend on pairwise constraint information, which is a matrix containing knowledge if data pairs can be in the same cluster or not. This paper introduces a novel embedding system named AutoEmbedder, that downsamples higher dimensional data to clusterable embedding points. To the best of our knowledge, this is the first research endeavor that relates to traditional classifier DNN architecture with a pairwise loss reduction technique. The training process is semi-supervised and uses Siamese network architecture to compute pairwise constraint loss in the feature learning phase. The AutoEmbedder outperforms most of the existing DNN based semi-supervised methods tested on famous datasets.

### Keywords:

* Deep Neural Network
* Unsupervised learning
* Semi-supervised learning
* Transfer learning
* Embedding
* Clustering
* Dimensionality reduction


An accuracy benchmark on CIFAR-10 dataset:

![benchmark](https://github.com/QuwsarOhi/AutoEmbedder/blob/master/benchmark_cifar10.png)


If you use this work, please cite this article:

[https://doi.org/10.1016/j.knosys.2020.106190](https://doi.org/10.1016/j.knosys.2020.106190)
