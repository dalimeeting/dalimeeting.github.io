---
title:  "Optimization"
layout: multitrack
abstract: ""
organizer_url: 
categories:
- dali2019b
organizers:
- given: Simon   
  family:  Lacoste-Julien
  url: http://www.iro.umontreal.ca/~slacoste/
  institute: U of Montreal
room: "Grey & Knysna Suite"
show_abstracts: true

talks:
- title: "A SGD Safari"
  author: 
  - family: Rosasco
    given: Lorenzo
    url: http://web.mit.edu/lrosasco/www/
    institute: MIT
  start: "09:30"
  end: "10:00" 
  abstract: "While stochastic gradient descent (SGD) is a workhorse in machine learning, the learning (test error) properties of many practically used variants are hardly known. In this presentation, we consider least squares learning and describe  steps to fill this gap focusing on the effect and interplay of  multiple passes, step-size choice and mini-batching. Our results show how these different flavors of SGD can be combined to achieve optimal learning errors, hence providing practical insights."
  slide: "http://www-labs.iro.umontreal.ca/~slacoste/dali/2019-01-03-Lorenzo-dali.pdf"
- title: "Training on the Test Set and Other Heresies"
  author:
  - given: Benjamin
    family: Recht
    url: https://people.eecs.berkeley.edu/~brecht/
    institute: UC Berkeley
  start: "10:00"
  end: "10:30" 
  abstract: "Conventional wisdom in machine learning taboos practices that are overwhelmingly common. For example, training on the test set, interpolating the training data, and optimizing to high precision are all considered bad methodology. This talk surveys empirical evidence demonstrating that conventional wisdom is wrong. I will show several examples where large, high-capacity models achieve state-of-the-art performance on many machine learning benchmarks. I will also show that models with low test error tend to have the best performance on new test data sets of unseen examples. However, I will also show that slightly shifting how the data is generated results in large drops in accuracy and increasing model size incurs significant diminishing returns. "
  slide: "http://www-labs.iro.umontreal.ca/~slacoste/dali/2019-01-03-Recht-dali.pdf"
- title: "Some success stories in bridging theory and practice in optimization"
  author:
  - given: Anima
    family: Anankumar
    url: http://tensorlab.cms.caltech.edu/users/anima/
    institute: Caltech
  start: "10:30"
  end: "11:00"   
  abstract: "With advent of deep learning, there are many gaps between theory and practice. Understanding optimization landscape of non-convex deep-learning loss functions is challenging. We present a few success stories that present both theoretical analyses and empirical results. We analyze signSGD: a gradient compression algorithm that only transmits the sign of the stochastic gradients during distributed training. This algorithm uses 32 times less communication per iteration than distributed SGD. We show that signSGD has nearly no loss in accuracy while yielding significant speedups. I will present a work that applies deep-learning in a control problem that guarantees stable landing of a drone. This approach blends together a nominal dynamics model coupled with a neural network that learns the unknown ground effect model. We show that spectral normalization of neural network guarantees stability and shows performance improvement in practice. "
  slide: "http://www-labs.iro.umontreal.ca/~slacoste/dali/2019-01-03-Anandkumar-dali.pdf"
- title: Coffee
  start: "11:00"
  end: "11:30"
- title: "Function norms and regularization in deep networks"
  author:
  - given: Matthew
    family: Blaschko
    url: http://homes.esat.kuleuven.be/~mblaschk/
    institute: KU Leuven
  start: "11:30"
  end: "12:00" 
  abstract: "Deep neural networks (DNNs) have become increasingly important due to their excellent empirical performance on a wide range of problems. However, regularization is generally achieved by indirect means, largely due to the complex set of functions defined by a network and the difficulty in measuring function complexity. There exists no method in the literature for additive regularization based on a norm of the function, as is classically considered in statistical learning theory. In this work, we propose sampling-based approximations to weighted function norms as regularizers for deep neural networks. We provide, to the best of our knowledge, the first proof in the literature of the NP-hardness of computing function norms of DNNs, motivating the necessity of an approximate approach. We then derive a generalization bound for functions trained with weighted norms and prove that a natural stochastic optimization strategy minimizes the bound."
- title: "Sufficient decrease is all you need"
  author:
  - given: Fabian
    family: Pedregosa 
    url: http://fa.bianp.net/
    institute: Google Brain Montreal
  start: "12:00"
  end: "12:30"
  abstract: "Most first-order optimization methods admit a step-size parameter that controls the magnitude of the update. Correctly tuning this parameter is crucial for the practical success of these methods: a step-size that is too small will result in unnecessarily slow convergence, while one that is too large might result in divergence. For some methods like gradient descent, classical techniques exist to set it, such as the Wolfe or sufficient decrease conditions. In this talk I revisit these classical techniques and propose two novel extensions for structured saddle-point problems and the Frank-Wolfe algorithm. I will finish by reviewing recent extensions to stochastic optimization."
  slide: "http://www-labs.iro.umontreal.ca/~slacoste/dali/2019-01-03-Pedregosa-dali.pdf"
- title: Discussion
  start: "12:30"
  end: "13:00"
- title: Lunch
  start: "13:00"
  end: "14:00"
- title: "Debiasing our Objective Functions"
  author:
  - given: Sebastian
    family:  Nowozin
    url: http://www.nowozin.net/sebastian/
    institute: MSR Cambridge, UK
  start: "17:00"
  end: "17:30" 
  abstract: "In many cases the objective functions we use in machine learning are expectations over iid data. In other cases they are stochastic approximations that are biased. I will use the field of approximate inference as example of such quantities and highlight that at its heart, the field of approximate inference is about trade-offs between computation and estimation accuracy: when we approximate quantities such as the evidence or posterior expectations no randomness is left and given limitless computation budget all quantities can be evaluated exactly. But given finite computation, how do we select inference methods such that they provide accurate estimates of quantities of interest? In this talk I will argue for a more explicit consideration of bias-variance tradeoffs of common inference methods. In particular, I highlight that current inference methods such as variational inference and Markov Chain Monte Carlo make a particular bias-variance tradeoffs which may be suboptimal for our inferential question at hand. What can we do about this? There is a rich portfolio of methods to change bias-variance tradeoffs in the form of debiasing methods; I will provide a brief overview and demonstrate a number of recent successful applications of these methods to variational inference and stochastic gradient MCMC."
  slide: "http://www-labs.iro.umontreal.ca/~slacoste/dali/2019-01-03-Nowozin-dali.pdf"
- title: "Extragradient and Negative Momentum to Optimize GANs"
  author:
  - given: Simon 
    family:  Lacoste-Julien
    url: http://www.iro.umontreal.ca/~slacoste/
    institute: U of Montreal
  start: "17:30"
  end: "18:00" 
  abstract: "Generative Adversarial Networks (GANs) are a popular generative modeling approach known for producing appealing samples, but for which training is known to be difficult. GANs were originially formulated as a smooth game optimization problem between two players, with different properties than standard minimization. Fortunately, these problems have been studied for a long time in the mathematical programming literature. In the first part of the talk, I will survey the variational inequality framework which contains most formulations of GANs introduced so far, and present theoretical and empirical results on adapting the standard methods (such as the extragradient method) from this literature to the training of GANs. In the second part, I will present a different novel technique, the use of negative momentum, to stabilize the dynamics of two player games, and provide a complete characterization of its behavior for bilinear games."
  slide: "http://www-labs.iro.umontreal.ca/~slacoste/dali/2019-01-03-Lacoste-Julien-dali.pdf"
- title: "On the Duality of Sampling and Newton's Method in Constrained Optimization."
  author:
  - given: Jacob
    family:  Abernethy
    url: https://www.cc.gatech.edu/~jabernethy9/
    institute: Georgia Tech
  start: "18:00"
  end: "18:30"  
  abstract: "A well-studied deterministic algorithmic technique for convex optimization is the class of so-called Interior Point Methods of Nesterov and Nemirovski, which involve taking a sequence of Newton steps along the 'central path' towards the optimum. An alternative randomized method, known as simulated annealing, involves performing a random walk around the set while 'cooling' the stationary distribution towards the optimum. We will show that these two methods are, in a certain sense, fully equivalent: both techniques can be viewed as different types of path following. This equivalence allows us to get an improved state-of-the-art rate for simulated annealing, and provides a new understanding of random walk methods using barrier functions."
  slide: "http://www-labs.iro.umontreal.ca/~slacoste/dali/2019-01-03-Abernethy-dali.pdf"
- title: Discussion
  start: "18:30"
  end: "19:00"
---
