# Variational-inference-on-MNIST
A list of variational inference algorithms and their performance on MNIST.

The common setting of doing variational inference is as following: given a set of data points x, we assume latent varable z and aim to recover the true poster p(z|x), which is analytically intractable.  We take an approximation distribution q(z) or q(z|x) from an tractable distribution family and let it approach the true posterior as "close" as possible. MNIST dataset is comprised of pictures features with handwritten digits, which is a common benchmark dataset. The performance of variational inference algorithms on MNIST are usually measured in terms of the maximum data-log likelihood they can achieve and the "quality" of their reconstruction pictures. 

This page aims to list up-to-date variational inference algorithms and their performance on MNIST. Contributions and comments are more than welcome. 

* 3D-ED-GAN - [Shape Inpainting using 3D Generative Adversarial Network and Recurrent Convolutional Networks](https://arxiv.org/abs/1711.06375) , test 
* 3D-GAN - [Learning a Probabilistic Latent Space of Object Shapes via 3D Generative-Adversarial Modeling](https://arxiv.org/abs/1610.07584) ([github](https://github.com/zck119/3dgan-release))
