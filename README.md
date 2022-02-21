# Autoencoders
Implementation of the linear, convolutional and variational autoencoders on the database on human faces http://vis-www.cs.umass.edu/lfw/.

As a result, I 

- implement and thrain the autoencoders
- perform the tSNE dimensionality reduction and visualisation on the latent space
- implement cheap image morphing of two randomly chosen images
- reconstruct new faces by choosing a random point in the latent space and decoding it


I thained the networks on GPU in Google Colab. The weights are saved in .hp5 files for each autoencoder.
