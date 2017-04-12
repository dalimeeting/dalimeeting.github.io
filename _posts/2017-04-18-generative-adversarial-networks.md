---
title:  "The Theory of Generative Adversarial Networks"
layout: multitrack
organizer_url:
abstract: "In Generative Adversarial Networks (GANs), two machines learn together about a probability distribution P by pursuing competing goals. On the one hand, the generator transforms vectors of random noise into samples that resemble the distribution P, according to the scores of the discriminator. On the other hand, the discriminator distinguishes between real samples drawn from P and fake samples synthesized by the generator. After training ends, the generator estimates an implicit generative model of the distribution P, and the discriminator estimates the energy landscape of the data.

Recent efforts have established connections between GAN training and f-divergence minimization, optimal transport, and energy-based learning. However, our theoretical understanding of GANs remains on its infancy, and many fascinating questions cry for an answer. How can we better understand the optimization dynamics of GANs? How can we evaluate the quality of a GAN? How to stabilize training of GANs? How to capture parameter uncertainty in the GAN framework, i.e. what is the analogue to the Bayesian neural network in the GAN setting?In this workshop, we will foster interesting discussions to ask ourselves these and many other questions."
categories:
- dali2017
organizers:
- given: Sebastian 
  family: Nowozin
  url: http://www.nowozin.net/sebastian/
  institute: Microsoft Research
- given: David
  family: Lopez Paz
  url: http://lopezpaz.org/
  institute: Facebook AI Research
room: Drago-Adeje
show_abstracts: true
talks:
- title: "Introduction"
  youtube: 
  start: "09:20"
  end: "09:30"
- title: "Two-Sample Tests, Integral Probability Metrics, and GAN Objective"
  author:
  - given: Dougal J.
    family: Sutherland
    institute: Gatsby unit, UCL
    url: http://www.gatsby.ucl.ac.uk/~dougals/
  youtube: 
  start: "09:30"
  end: "10:00"
  abstract: "One of the major failure patterns of typical GAN models is when the generator
collapses to a single point considered highly realistic by the current
discriminator, after which the learning problem becomes stuck. To help avoid
this issue, we can replace the discriminator with a function that looks at an
entire sample set at a time, so that no single point becomes attractive to the
generator. Doing so brings us into the well-studied realm of two-sample
testing. This talk will discuss several different techniques for two-sample
testing and their application in GAN settings, including classifier-based two
sample tests which correspond to the traditional GAN, the maximum mean
discrepancy, and Wasserstein distances. We will also discuss the use of these
types of distances as tools to diagnose convergence of generative models and
discover ways in which their samples differ from the reference distribution."
- title: "Connecting GANs, Actor-Critic Methods and Multilevel Optimization"
  author:
  - given: David
    family: Pfau
    institute: Deepmind
    url: http://davidpfau.com/
  youtube: 
  start: "10:00"
  end: "10:30"
  abstract: "Generative Adversarial Networks pose a challenging optimization problem due to
the multiple loss functions which must be optimized simultaneously. The GAN
game can be framed as a bilevel optimization problem, like many other problems
currently of interest to the deep learning community. We show that there is a
close connection between GANs and actor-critic methods for continuous control
such as deep deterministic policy gradients, and suggest that generic
optimization tricks may help stabilize both classes of models. Towards this
goal, we introduce unrolled GANs, an algorithm for GAN training which
approximates gradients with respect to the optimal discriminator by
backpropagating through several steps of SGD."
- title: "AdaGAN: Boosting Generative Models"
  author:
  - given: Olivier
    family: Bousquet
    institute: Google
    url: https://research.google.com/pubs/OlivierBousquet.html
  youtube: 
  start: "10:30"
  end: "11:00"
  abstract: "Generative Adversarial Networks (GAN) (Goodfellow et al., 2014) are an
effective method for training generative models of complex data such as
natural images. However, they are notoriously hard to train and can suffer
from the problem of missing modes where the model is not able to produce
examples in certain regions of the space. We propose an iterative procedure,
called AdaGAN, where at every step we add a new component into a mixture model
by running a GAN algorithm on a reweighted sample. This is inspired by
boosting algorithms, where many potentially weak individual predictors are
greedily aggregated to form a strong composite predictor. We prove that such
an incremental procedure leads to convergence to the true distribution in a
finite number of steps if each step is optimal, and convergence at an
exponential rate otherwise. We also illustrate experimentally that this
procedure addresses the problem of missing modes."
- title: "Image Superresolution: from mean squared error to variational inference with GANs"
  author:
  - given: Ferenc
    family: Huszár
    institute: Twitter Cortex
    url: http://www.inference.vc/about/
  youtube: 
  start: "11:30"
  end: "12:00"
  abstract: "Like many other problems, convolutional neural networks have achieved state of
the art performance in photo-realistic image superresolution. The main
limitation of early methods was that they minimise mean square reconstruction
error, which is known to be a poor proxy to perceptual quality. Newer methods,
based on generative adversarial networks produce significantly more
perceptually accurate results.

This talk is about understanding why GANs work so well for image
superresolution and what they really do. I will first show how GANs can be
used to approximate MAP inference in the SR problem, and then show how a
simple stochastic extension of existing methods can be shown to perform
variational inference. In the second half of the talk I'm going to talk about
a generalisation of this idea: using implicit models in variational inference."
- title: "Generator-Aware Discriminators for Stable GAN Training"
  author: 
  - given: David
    family: Duvenaud
    institute: Toronto
    url: https://www.cs.toronto.edu/~duvenaud/
  youtube: 
  start: "12:00"
  end: "12:30"
  abstract: "The alternating optimization of generator and discriminator produces sometimes
unfavorable training dynamics.  In particular, as the generator changes, the
discriminator forgets how to discriminate against previously-seen generators.
We examine the idea of training a single universal discriminator, who takes as
an extra argument the weights of the generator network.  We also explore a
similar idea for training variational recognition networks when integrating
over the generator weights."
- title: "Semi-Supervised Learning with Context-Conditional Generative Adversarial Networks"
  author:
  - given: Emily
    family: Denton
    institute: NYU
    url: http://www.cs.nyu.edu/~denton/
  youtube: 
  start: "12:30"
  end: "13:00"
  abstract: "The main focus of this talk will be on a simple semi-supervised learning
approach for images based on in-painting using an adversarial loss. Images with
random patches removed are presented to a generator whose task is to fill in
the hole, based on the surrounding pixels. The in-painted images are then
presented to a discriminator network that judges if they are real (unaltered
training images) or not. This task acts as a regularizer for standard
supervised training of the discriminator. Using our approach we are able to
directly train large VGG-style discriminator networks in a semi-supervised
fashion, obtaining competitive results on STL-10 and PASCAL datasets."
- title: "Intrinsic Motivation and Automatic Curricula via Asymmetric Self-Play"
  author: 
  - given: Arthur 
    family: Szlam
    institute: Facebook
    url: https://research.fb.com/people/szlam-arthur/
  youtube: 
  start: "18:00"
  end: "18:30"
  abstract: "I will discuss how an agent can learn to manipulate its environment by
proposing itself tasks to complete.   In tabular, in Markovian environments
that are reversible or resetable, with an appropriate choice of reward
function, the agent learns to transition from any state to any other as
efficiently as possible.  I will further discuss our experiments showing that
in more complex environments that this unsupervised training can reduce the
number of episodes needed to learn extrinsic tasks.  Joint work with Sainbayar
Sukhbaatar, Ilya Kostrikov, and Rob Fergus."
- title: "On Generative Adversarial Networks and Density Estimation"
  author:
  - given: Fernando
    family: Perez-Cruz
    institute: Stevens Institute of Technology
    url: www.tsc.uc3m.es/~fernando/
  youtube: 
  start: "18:30"
  end: "19:00"
  abstract: "Generative adversarial networks (GANs) propose an alternative approach for
density estimation that relies on a discriminative network's output to lead
a generativenetwork's density model. They seem to be able to tackle density
estimation in high dimensional spaces with limited number of training samples.
In this paper, we analyze the accuracy of GANs in estimating the underlying
density of the training samples. We focus on both the asymptotically analysis
and an empirical study with a state-of-the-art GAN implementation. For the
former, we show a limitation in the proof of convergence in (Goodfellow et
al., 2014) that might prevent the GAN density estimation from converging to
the true density as the number of samples increases. For the latter, we
advocate for a two-sample test as the proper test for measuring GANs
performance, since it is a simple test would tell us if two set of samples
come from the same distribution."
- title: "Brainstorming and discussion"
  youtube: 
  start: "19:00"
  end: "20:00"
speakers:
- Dougal Sutherland  
- Ferenc Huszár 
- Emily Denton
- David Pfau 
- Olivier Bousquet 
- David Duvenaud
- Arthur Szlam
- Fernando Perez-Cruz
---
