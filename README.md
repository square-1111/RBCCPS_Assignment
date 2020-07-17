# Denoising Autoencoder
A Keras implementation of Denoising Autoencoder. Aim is to denoise CIFAR-10 images. Based on Deep Convolution Network we input noised image and gets an denoised output.
* Gaussian Noise with a scaling factor = 0.3 is added to the CIFAR-10 dataset.
* Autoencoder has an encoder and a decoder with a skip connection for smooth loss optimization.
* Training Epochs = 100
* Adam Optimizer, with a learning rate of 0.001, optimizes binary cross entropy loss. 