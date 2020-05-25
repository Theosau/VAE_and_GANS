This repository contains the 2nd Deep Learning coursework from the Department of Computing, Imperial College London, Academic Year 2019-2020, delivered by Professor Michael Bronstein, Professor Bjorn Schuller, and Stefanos Zafeirou. The coursework was developed with their PhD students. 

# VAE_and_GANS

The first part consists of the implementation of a Variational Autoencoder on the MNIST dataset. <br>
The details of the implementation are found in the in the VAE_and_GANS.ipynb notebook with thorough analysis on the latent space representation and the loss function and the two distinct error terms (of the evidence lower bound loss: the reconstruction error and the Kullback Lieblers Divergence (KLD) between the approximate posterior and the set prior on the latent space distribution).  <br>
Posterior collapse is also discussed.

The seconde part consists of the implementation of a Deep Convolutional GAN on the CIFAR-10 dataset. <br>
Important features used in the DCGAN are: <br>
- Data Augmentation
- Batch Normalisation
- Leaky ReLU for the decoder
- Learning Rate scheduler

The rational behind these features is described in the VAE_and_GANS.ipynb notebook. <br> 
The evolution of the loss functions of both the discriminator and the genrator, mode collapse and convergence collapsed are also disucussed.

Don't forget to have a look at the beautiful animal shapes in the images folder. I have observed the latter while visualising the latent representation using two dimensions t-SNE with different KLD error beta weights and latent representation dimensions.
