# Clustering <br>
****ICBP(Image Clustering Algorithm Based on Predefined
Evenly-Distributed Class Centroids)****

This is a reproducing code for ICBPC.
The clustering algorithm based on deep neural network clusters
by obtaining the optimal feature representation,but the clustering performance is still not ideal in the face of the complexity of the image.This paper
presents an image clustering algorithm based on predefined evenly-distributed class centroids(PEDCC) and composite cosine distance.Compared with current popular auto-encoder structure, we design an encoder only network structure with normalized latent features, and two effective loss functions in latent feature space by replacing the Euclidean distance with cosine distance.We find that (1) contrastive learning plays a key role in clustering algorithm and greatly improves the quality of learning latent features; (2)Compared with Euclidean distance, composite cosine distance can be more suitable for the normalized latent features and PEDCC-based Maximum Mean
Discrepancy(MMD) loss function.

# Requirements <br>
You must have the following already installed on your system. <br><br>

1、Pytorch 1.0 <br>
2、sklearn <br>
3、python 3.6 <br>

***

# Quick start <br>
For reproducing the experiments on MNIST、Fashion-Mnist、COIL20 datasets and cifar-10, run the following codes. <br><br>

1、python PEDCC.py : to Initialize the PEDCC, You need to set the cluster number, and every kind of dimension. We suggest that the MNIST every picture extract 60 dimension feature vector. <br>
2、Modify data_transform.py: you should choose datasets. <br>
3、python main.py for training. <br>


***


## If you have any questions, you can email me by hlh8217@shu.edu.cn
