# Variational-inference-on-MNIST
A list of variational inference algorithms and their performance on MNIST.

The common setting of doing variational inference is as following: given a set of data points x, we assume latent varable z and aim to recover the true poster p(z|x), which is analytically intractable.  We take an approximation distribution q(z) or q(z|x) from an tractable distribution family and let it approach the true posterior as "close" as possible. MNIST dataset is comprised of pictures features with handwritten digits, which is a common benchmark dataset. The performance of variational inference algorithms on MNIST are usually measured in terms of the maximum data-log likelihood they can achieve and the "quality" of their reconstruction pictures. 

This page aims to list up-to-date variational inference algorithms and their performance on MNIST in roughly time order. Contributions and comments are more than welcome.  "NLL" denotes "negative log likelihood".

* SBAI - [Stochastic Backpropagation and Approximate Inference in Deep Generative Models ICML 2014](https://arxiv.org/abs/1401.4082)
* VAE - [Auto-Encoding Variational Bayes ICLR 2014](https://arxiv.org/abs/1312.6114)

* VINF - [Variational Inference with Normalizing Flows ICML 2015](https://arxiv.org/abs/1505.05770), DLGM+NF 85.1, DLGM+NICE 87.2, DLGM + HVI 85.51, DARN 84.13
* Review - [Markov Chain Monte Carlo and Variational Inference: Bridging the Gap, ICML 2015](https://arxiv.org/abs/1410.6460)

* Importance weighted VAE - [Importance Weighted Autoencoders, ICLR2016](https://arxiv.org/abs/1509.00519), VAE 84.78, IWAE 82.90
* A-DGM - [Auxiliary Deep Generative Models ICML 2016](https://arxiv.org/abs/1602.05473)
* IAF - [Improved Variational Inference with Inverse Autoregressive Flow, NIPS 2016](https://arxiv.org/abs/1606.04934), Convolutional VAE + HVI 81.94, DLGM 2hl + IWAE 82.90, LVAE 81.74, IAF 79.10

* Review paper - [On the Quantitative Analysis of Decoder-Based Generative Models ICLR 2017](https://arxiv.org/abs/1611.04273), AIS 85.679, AIS+Encoder 85.754, IWAE 86.902
* AVB - [Adversarial Variational Bayes: Unifying Variational Autoencoders and Generative Adversarial Networks, ICML 2017](https://arxiv.org/abs/1701.04722), AVB+AC 80.2, VAE 81.9, VAE+IAF 79.1
* Alice - [ALICE: Towards Understanding Adversarial Learning for Joint Distribution Matching NIPS 2017](https://arxiv.org/abs/1709.01215)
* VAE-SVGD - [VAE Learning via Stein Variational Gradient Descent NIPS 2017](https://arxiv.org/abs/1704.05155), Stein VIWAE 82.88 

* SIVI - [Semi-Implicit Variational Inference, ICML 2018](https://arxiv.org/abs/1805.11183)
* KIVI - [Kernel Implicit Variational Inference, ICLR 2018](https://arxiv.org/abs/1705.10119)
* CTF - [Continuous-Time Flows for Efficient Inference and Density Estimation ICML 2018](https://arxiv.org/abs/1709.01179)
* CVB - [Coupled Variational Bayes via Optimization Embedding, NIPS 2018], CVB 70.1

* UIVI - [Unbiased Implicit Variational Inference, Submitted AISTATS 2019](https://arxiv.org/abs/1808.02078), VAE 98.29, SIVI, 97.77, UIVI 94.09
* DDNF - [Deep Diffeomorphic Normalizing Flows](https://arxiv.org/abs/1810.03256)
* MD-GAN - [Mixture Density Generative Adversarial Networks](https://arxiv.org/abs/1811.00152)
* VI-ID - [Variational Inference using Implicit Distributions](https://arxiv.org/abs/1702.08235)
* DSIVI - [Doubly Semi-Implicit Variational Inference](https://arxiv.org/abs/1810.02789)
