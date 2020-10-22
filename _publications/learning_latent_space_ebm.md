---
title: "Learning Latent Space Energy-Based Prior Model"
collection: publications
permalink: /publications/learning_latent_space_ebm
venue: "NeurIPS 2020"
citation: '<b>Bo Pang</b>, Tian Han, Erik Nijkamp, Song-Chun Zhu, and Ying Nian Wu. <b>NeurIPS 2020</b>.'
---


## Abstract
The generator model assumes that the observed example is generated by a low-dimensional latent vector via a top-down network, and the latent vector follows a simple and known prior distribution, such as uniform or Gaussian white noise distribution. While we can learn an expressive top-down network to map the prior distribution to the data distribution, we can also learn an expressive prior model instead of assuming a given prior distribution. This follows the philosophy of empirical Bayes where the prior model is learned from the observed data. We propose to learn an energy-based prior model for the latent vector, where the energy function is parametrized by a very simple multi-layer perceptron. Due to the low-dimensionality of the latent space, learning a latent space energy-based prior model proves to be both feasible and desirable. In this paper, we develop the maximum likelihood learning algorithm and its variation based on short-run Markov chain Monte Carlo sampling from the prior and the posterior distributions of the latent vector, and we show that the learned model exhibits strong performance in terms of image and text generation and anomaly detection.