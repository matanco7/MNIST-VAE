# MNIST-VAE

Implementation of "Semi-supervised Learning with
Deep Generative Models", by Kingsma et al. https://arxiv.org/abs/1406.5298.
In this work we implement M1 scheme as described in Algorithm1.
A VAE was trained  on the Fashion MNIST dataset. The latent space vector outputs of the VAE were used for training the SVM.
A Radial basis function kernel was chosen for the SVM. Test set's accuracy is increasing with data set size.

