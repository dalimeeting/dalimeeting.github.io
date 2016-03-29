---
title:  "Learning and Optimization"
layout: workshop
organizer_url: 
categories:
- dali2016
organizers:
- firstname: Stefanie
  lastname: Jegelka
  url: "http://people.csail.mit.edu/stefje/"
  institute: Massachusetts Institute of Technology
- firstname: Guillaume
  lastname: Obozinski
  url: "http://imagine.enpc.fr/~obozinsg/"
  institute: Ecole des Ponts - ParisTech
show_abstracts: true
talks:
- title: "Primal-Dual Rates and Certificates"
  speaker: "Martin Jaggi"
  start: "09:30"
  end: "10:05"
  abstract: "We propose an algorithm-independent framework to equip existing optimization methods with primal-dual certificates. Such certificates and corresponding rate of convergence guarantees are important for practitioners to diagnose progress, in particular in machine learning applications. We obtain new primal-dual convergence rates e.g. for the Lasso as well as many L1, Elastic-Net and group-lasso-regularized problems. The theory applies to any norm-regularized generalized linear model. Our approach provides efficiently computable duality gaps which are globally defined, without modifying the original problems in the region of interest."
- title: "Generalization properties of multiple passes stochastic gradient method"
  speaker: "Silvia Villa"
  start: "10:05"
  end: "10:40"
  abstract: "The stochastic gradient method has become an algorithm of choice in machine learning, because of  its simplicity and small computational cost, especially when dealing with big data sets. Despite   its widespread use, the  generalization properties of the variants of stochastic gradient method used in practice are relatively little understood.  Most previous works consider generalization properties of SGM with only one pass over the data, while in practice  multiple passes are usually considered. The effect of multiple passes has  been studied extensively for the optimization  of an empirical objective, but the role for generalization is less clear. In this talk, we start filling this gap studying the generalization properties of multiple passes stochastic gradient method for least square regression in an abstract non parametric setting. We show that,  if all other parameters are fixed a priori, the number of passes over the data indeed acts as a regularization parameter. The obtained bounds are sharp  and matches those obtained with other regularized techniques such as ridge regression."
- title: "Minimizing the Maximal Loss: Why and How ?"
  speaker: "Shai Shalev-Shwartz"
  start: "10:40"
  end: "11:15"
  abstract: "We argue that in some situations, minimizing the maximal loss over the training set is essential for achieving good performance on unseen examples. We present a stochastic algorithm for solving the resulted optimization problem."
- title: ""
  start: "Coffee Break"
- title: ""
  speaker: "Andreas Krause"
  start: "11:45"
  end: "12:20"
- title: "On the Global Linear Convergence of Frank-Wolfe Optimization Variants"
  speaker: "Simon Lacoste-Julien"
  start: "12:20"
  end: "12:55"
- title: ""
  start: "Lunch and Afternoon Activities"
- title: "Submodular Functions: from Discrete to Continous Domains"
  speaker: "Francis Bach"
  start: "18:00"
  end: "18:35"
  abstract: "Submodular set-functions have many applications in combinatorial optimization, as they can be minimized and approximately maximized in polynomial time. A key element in many of the algorithms and analyses is the possibility of extending the submodular set-function to a convex function, which opens up tools from convex optimization. Submodularity goes beyond set-functions and has naturally been considered for problems with multiple labels or for functions defined on continuous domains, where it corresponds essentially to cross second-derivatives being nonpositive. In this paper, we show that most results relating submodularity and convexity for set-functions can be extended to all submodular functions. In particular, (a) we naturally define a continuous extension in a set of probability measures, (b) show that the extension is convex if and only if the original function is submodular, (c) prove that the problem of minimizing a submodular function is equivalent to a typically non-smooth convex optimization problem, and (d) propose another convex optimization problem with better computational properties (e.g., a smooth dual problem). Most of these extensions from the set-function situation are obtained by drawing links with the theory of multi-marginal optimal transport, which provides also a new interpretation of existing results for set-functions. We then provide practical algorithms to minimize generic submodular functions on discrete domains, with associated convergence rates. (available at https://hal.archives-ouvertes.fr/hal-01222319v2/document)"
- title: "MetaGrad: Faster Convergence Without Curvature in Online Convex Optimization"
  speaker: "Wouter M. Koolen"
  start: "18:35"
  end: "19:10"
- title: "Less is more: optimal learning with stochastic projection regularization"
  speaker: "Lorenzo Rosasco"
  start: "19:10"
  end: "19:45"
  abstract: "In this talk, we will discuss the generalization properies of commonly used techniques to scale up kernel methods and Gaussian processes. In particular, we will focus on data dependent and independent sub-sampling methods, namely Nystrom and random features, and study their generalization properties within a statistical learning theory framework. On the one hand we show that these methods can achieve optimal learning errors while being computational efficient. On the other hand, we show that subsampling can be seen as a form of stochastic projection regularization, rather than only a way to speed up computations."
- title: ""
  start: "Dinner"
speakers:
- Francis Bach
- Martin Jaggi
- Wouter M. Koolen
- Andreas Krause
- Simon Lacoste-Julien
- Lorenzo Rosasco
- Shai Shalev-Shwartz
- Silvia Villa
---
