# Generative Models

A generative model is a probability distribution $p(x)$ of some samples (e.g., images in MNIST). The idea is that we can generate new samples if we know $p(x)$.

To generate samples, we can learn $p(x)$ explicitly (e.g., VAE, PixelCNN) or implicitly (e.g., GAN). In this section, we're going to get through **VAE** and **GAN** to help people understand how generative models work to generate samples.

### References
[1] [pytorch examples](https://github.com/pytorch/examples)  
[2] [CS231n](http://cs231n.stanford.edu/)  
[3] [Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)  
[4] [Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434) 
