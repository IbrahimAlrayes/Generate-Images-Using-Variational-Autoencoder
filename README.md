# VAE-tutorial
A simple tutorial of Variational AutoEncoder(VAE) models. This repository contains the implementations of following VAE families.


* [Variational AutoEncoder](https://arxiv.org/pdf/1312.6114.pdf) (VAE, D.P. Kingma et. al., 2013)
* [Vector Quantized Variational AutoEncoder](https://arxiv.org/pdf/1711.00937.pdf) (VQ-VAE, A. Oord et. al., 2017)

# Requirements
* [Anaconda](https://www.anaconda.com/products/individual#Downloads)
* python=3.7
* [pytorch](https://pytorch.org/)=1.7
* tqdm
* numpy

# How-to-use
simply run the <file_name>.ipynb files using jupyter notebook.

# Experimental Results
## Variational AutoEncoder (VAE)
- trained on MNIST dataset for 20 epochs
- groundtruth(left) vs. generated(reconstructed, right)

![VAE_ground_truth](./assets/VAE_ground_truth.png) ![VAE_reconstructed](./assets/VAE_reconstructed.png)

- generated random samples from noise vector

![VAE_generated_sample](./assets/VAE_generated_random_sample.png)


