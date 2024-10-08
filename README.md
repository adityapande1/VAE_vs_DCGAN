# Generative-Models-Comprehensive-Study


#### NOTE
This project is done as a part of course assignment for<br>
 Course : __CS 726: Advanced Machine Learning__ <br>
 Instructor :  __Prof. Sunita Sarwagi__ at __IIT Bombay__

## Description
The project aims at understanding the generative paradigms of deep learning specifically DDPMs, Variational Auto Encoders (VAEs) and Generative Adversarial Networks (GANs), by implementing these architectures from scratch, training them and performing a comparitive study.

#### Diffusion Model
Diffusion models are generative models that create complex data by gradually transforming Gaussian noise into structured data. They consist of a forward process where noise is added to the data and a reverse process where the model learns to denoise and recover the original data. These models have been effective in generating high-quality images, audio, and other data types.

#### DC-GAN
A Deep Convolutional GAN (DCGAN) uses deep convolutional networks to generate realistic images. It consists of a generator, which creates images from random noise, and a discriminator, which distinguishes between real and fake images. Through adversarial training, both networks improve, enabling DCGANs to produce high-quality images.<br><br>

#### VAE
A Variational Autoencoder (VAE) is a type of generative model that learns to encode input data into a latent space and then reconstructs it. Unlike traditional autoencoders, VAEs add a probabilistic element by mapping inputs to a distribution, allowing for the generation of new data by sampling from this distribution. This makes VAEs effective for tasks like image generation and anomaly detection.<br>

