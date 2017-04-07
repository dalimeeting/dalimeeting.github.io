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
room: Adeje
show_abstracts: true
talks:
- title: "Two-Sample Tests, Integral Probability Metrics, and GAN Objective"
  speaker: "Dougal J. Sutherland (Gatsby unit, UCL)"
  youtube: 
  start: 
  end:
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
- title: "Image Superresolution: from mean squared error to variational inference with GANs"
  speaker: "Ferenc Huszar (Twitter Cortex)"
  youtube: 
  start: 
  end:
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
