---
title: Stochastic Modeling and Bayesian Inference. Part I
author: Bizovi Mihai
date: '2017-08-07'
abstract: "Current challenges in economics need an interdisciplinary, multidimensional approach and different perspectives. The thesis investigates statistical modeling based on three schools of thought: Stochastic Modeling, Machine Learning and Bayesian Analysis, which has applications from economics and finance to genetics, linguistics and artificial intelligence.


This approach is extremely general and allows us to make inferences about latent quantitites and relationships, to identify what is hidden beneath surface, to account for the uncertainty and nonlinearities of economic phenomena. The idea of learning from data, the flexibility of such models and the parsimonity principle could lead to a kind of modeling which was impossible with classical tools. The focus will be very much on models and a deep understanding of concepts on which they're built."
slug: stochastic
categories: ["stochastic"]
tags: ["bayesian", "ml"]
---

The first series of posts gives an overview of the probabilistic perspective on Machine Learning, which is exactly what my bachelor thesis ^[Bizovi Mihai - Stochastic Modeling and Bayesian Inference (2017, Thesis)] is about. 

> ”I can live with doubt and uncertainty and not knowing. We absolutely must leave room for doubt or there is no progress and there is no learning. There is no learning without having to pose a question. And a question requires doubt. People search for certainty, but there is no certainty.”
— Richard Feynman *The pleasure of finding things out*



## The need for stochastic modeling and Bayesian thinking

The ugly truth is that humans are not good at prediction, neither consistent with probability theory. We are "suffering" from multiple evolutionary mechanisms, cognitive biases and even statisticians, formally trained in the language of uncertainty, aren't guarded against pitfalls that arise in practice and everyday life.

The same story is in reconciliation of new evidence with prior beliefs, processing multidimensional data, ignorance of feedback loops, dynamics and nonlinearities. The reason we are building models is to better understand the world, phenomena aroud us and in the end to improve our mental representations. Predictions that are less wrong usually take into account a variety of perspectives, a proven fact in ensemble modeling.


Machine learning models have become an essential part of online services and is taking over new fields, bringing firms and people lots of value. The multidimensional approach is what makes all this possible. In contrast with classical stats and NHST (Null Hypothesis Significance Testing), our focus will be on generalization performance and the idea of a model. Even though these models have their roots in statistics, the field is emerging as something more.

An important extension for which there is an acute need is dynamical models. A lot of interesting problems are multidimensional time series, which might invalidate the hypotheses behid classical data mining models. Coupled with the need of accounting for uncertainty, this brings us to the idea of introducing **stochastic** elements and to extend the idea of **learning** and **generalization**.

The third perspective which brings together stochastic elements with machine learning is *bayesian inference*, as a method to update beliefs and knowledge based on data from different sources. Bayesian modeling enables us to build hierarchical models with latent structures, while encoding the uncertainty in parameters and operating with probability distributions. 

On the shoulders of these three "giants", a stochastic perspective over Machine Learning emerges over the last two decades, which is flexible, general and more transparent than neural networks, works on thin data. There are several reasons the field is not yet in the mainstream: scalability and complexity of the models, in the sense of necessary knowledge and skill to start modeling. Once the software implementations, approximation methods and probabilistic programming languages will become better, the Bayesian methods will see another rise in popularity.


The next posts will be dedicated to each of these fundamental perspectives, in which we'll try to get to the essence. The last ones from this series will be on supervised and usupervised probabilistic models such as Gaussian Processes and Mixture Models. An essential concept will be the ARD (Automatic Relevance Determination) and Kernels which encourage sparse solutions.












