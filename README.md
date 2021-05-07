# ICBP
ICBP algorithm is an improvement of the ICAE algorithm, in which only the encoder is used to simplifying network structure, and the loss functions are improved based on cosine distance to achieves better clustering effect. Because the decoder is discarded, we no longer use reconstruction constraint loss and Sobel Smooth Loss.The contastive loss and MAE loss are used to make latent features similar between samples and its augmented samples.When we use contrastive loss and MMD, cosine distance is used to replace Eucilidean distance to better fit the PEDCC model.
Requirements 
You must have the following already installed on your system. 

1、Pytorch 1.0 
2、sklearn 
3、python 3.6 
Quick start 
For reproducing the experiments on MNIST、Fashion-Mnist、COIL20 datasets and cifar-10, run the following codes. 

1、python PEDCC.py : to Initialize the PEDCC, You need to set the cluster number, and every kind of dimension. We suggest that the MNIST every picture extract 60 dimension feature vector. 
2、Modify data_transform.py: you should choose datasets. 
3、python main.py for training. 
4、python feature2.py to calculate ACC and NMI. 
If you have any questions, you can email me by hlh8217@shu.edu.cn
