# ICBP
ICBP algorithm is an improvement of the ICAE algorithm, in which only the encoder is used to simplifying network structure, and the loss functions are improved based on cosine distance to achieves better clustering effect. Because the decoder is discarded, we no longer use reconstruction constraint loss and Sobel Smooth Loss.The contastive loss and MAE loss are used to make latent features similar between samples and its augmented samples.When we use contrastive loss and MMD, cosine distance is used to replace Eucilidean distance to better fit the PEDCC model.
