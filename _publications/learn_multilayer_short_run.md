---
title: "Learning Multi-Layer Latent Variable Model via Variational Optimization of Short Run MCMC for Approximate Inference"
collection: publications
permalink: /publications/learn_multilayer_short_run
venue: "ECCV 2020"
citation: 'Erik Nijkamp, <b>Bo Pang</b>, Linqi Zhou, Tian Han, Song-Chun Zhu, and Ying Nian Wu. <b>ECCV 2020</b>.'
---


## Abstract
This paper studies the fundamental problem of learning deep generative models that consist of multiple layers of latent variables organized in top-down architectures. Such models have high expressivity and allow for learning hierarchical representations. Learning such a generative model requires inferring the latent variables for each training example based on the posterior distribution of these latent variables. The inference typically requires Markov chain Monte Caro (MCMC) that can be time consuming. In this paper, we propose to use noise initialized non-persistent short run MCMC, such as finite step Langevin dynamics initialized from the prior distribution of the latent variables, as an approximate inference engine, where the step size of the Langevin dynamics is variationally optimized by minimizing the Kullback-Leibler divergence between the distribution produced by the short run MCMC and the posterior distribution. Our experiments show that the proposed method outperforms variational auto-encoder (VAE) in terms of reconstruction error and synthesis quality. The advantage of the proposed method is that it is simple and automatic without the need to design an inference model.
