---
title:  "Uncovering the structure of complex data: progresses in machine learning and causal inference"
abstract: "Inferring a system’s underlying mechanisms is a primary goal in many areas of science. For instance, understanding cause-effect relationships is necessary if one wants to intervene on the system in order to improve its performance. In this context, scientists often need to be able to draw causal interpretations from complex, real-world data.
Causal inference and structural equation models provide a rigorous framework to address these questions. However, the validity of these approaches may be challenged by complex structures involving non-stationarity, non-linearity or high-dimensionality. In particular, these properties frequently occur in natural or artificial systems resulting from interactions between many interdependent parts, such as biological or social networks.
This workshop will discuss recent progresses in causal inference and related approaches to deal with data of increasing complexity. It aims at bringing together researchers from various fields to discuss the current challenges in estimating mechanisms from real-world data." 
layout: multitrack
organizer_url: 
categories:
- dali2017
organizers:
- family: Besserve
  given: Michel 
  url: https://ei.is.tuebingen.mpg.de/person/besserve
  institute: Max Planck Institute for Intelligent Systems
- family: Heinze-Deml
  given: Christina 
  url: http://stat.ethz.ch/~heinzec/
  institute: ETH Zurich
room: Caleta
show_abstracts: true
talks:
- title: "Exact Constraint-based Causal Discovery"
  author:
  - given: Antti
    family: Hyttinen
    url: https://sites.google.com/site/ajhyttin/
    institute: Helsinki Institute for Information Technology
  youtube: 
  start: "09:30"
  end: "10:00"
  abstract: "Causal graphical model structure discovery is a challenging part of causal inference, graphical model research and machine learning. If absence of latent confounders can be assumed, the tool of choice are exact score-based methods, as they provably find the globally optimal equivalence class of structures. Constraint-based methods on the other hand are able to handle more general model spaces with cycles and latent confounders, but offer seriously poorer accuracy. We present research that bridges this gap between constraint-based and score-based methods to some extent. We use a combination of score-based and constraint-based ideas together with Boolean (maximum) satisfiability solving, to obtain an approach that retains exactness and the generality of the model space."
- title: "TBA"
  author:
  - given: Suchi
    family: Saria
    url: https://www.cs.jhu.edu/faculty/suchi-saria/
    institute: Johns Hopkins
  youtube: 
  start: "10:00"
  end: "10:30"
  abstract: 
- title: "Causal discovery and prediction in nonstationary environments"
  author:
  - given: Kun
    family: Zhang
    url: http://is.tuebingen.mpg.de/person/kzhang
    institute: Carnegie Mellon University & Max Planck Institute for Intelligent Systems
  youtube: 
  start: "10:30"
  end: "11:00"
  abstract: "Time series data and data collected across different conditions often exhibit a distribution shift phenomenon, which poses challenges for both causal discovery and prediction -- the underlying causal model may change with the distribution shift, and traditional supervised learning assumes that the training set and test set were drawn from the same distribution, which is not the case when the data distribution changes. In this talk, we emphasize and exploit the coupling relationship between causal modeling and distribution shift: causal models imply how the data-generating processes or different modules of the joint distribution may change, and distribution shift actually exhibits such changes. Accordingly, we show how causal discovery could benefit from distribution shift, and how a causal perspective helps understand and solve the problem of domain adaptation or transfer learning."
- title: "Causal Inference from Single Cell, Mass Cytometry Data: an Integrative Approach"
  author:
  - given: Ioannis
    family: Tsamardinos
    url: http://mensxmachina.org/en/people/ioannis-tsamardinos/
    institute: University of Crete
  youtube: 
  start: "11:30"
  end: "12:00"
  abstract: "Single Cell biological data, and particularly Mass Cytometry Data present significant opportunities not only for discovering novel biological data, but also for serving as a testbed of Causal Discovery algorithms. Such data seem ideal for Causal Discovery as they typically contain thousands of even millions of sample points, under several experimental conditions, and often measured at several time points. On the other hand, initial attempts at Causal Discovery demonstrate the challenges of learning causality in the microworld where confounding factors and feedback cycles are abundant. In this talk, we present approaches developed and applied on mass cytometry data that are based on Causal Probabilistic Graphical Models as well as novel approaches based on Ordinary Differential Equation Models. The results and the lesson's learnt will be discussed, as well as their influence in inventing new methods that can robustly discover causality in single cell biological data."
- title: "TBA"
  author:
  - given: Joris 
    family: Mooji
    url: https://ei.is.tuebingen.mpg.de/~jorism
    institute: Max Planck Institute for Intelligent Systems
  youtube: 
  start: "12:00"
  end: "12:30"
  abstract: ""
- title: "Large-scale causal discovery from nonlinear time series datasets"
  author:
  - given: Jacob  
    family: Runge
    url: http://www.imperial.ac.uk/people/j.runge
    institute: Imperial Collegue
  youtube: 
  start: "12:30"
  end: "13:00"
  abstract: "Detecting causal associations in observational time series datasets is a key challenge for novel insights into complex dynamical systems such as the Earth system. Dependencies in such a high-dimensional dynamical system may involve time-delays, nonlinearity, and strong autocorrelations, which present major challenges for causal discovery techniques. Here we are interested in time-lagged causal discovery using conditional independence testing and address two major problems: (1) Low power due to high-dimensionality and (2) detection `biases'. The latter refers to the problem that the detection power for individual links may depend not only on their causal strength, but also on autocorrelation and other dependencies. Here we introduce a method for large-scale, linear and nonlinear, time-delayed causal discovery. In extensive numerical experiments we find that our method yields more power than common methods and largely overcomes detection biases allowing to more accurately rank associations in large-scale analyses by their causal strength. We demonstrate the method on a large-scale climate time series dataset."
  
speakers:
- Jakob Runge, Imperial College, London
- Joris Mooij, University of Amsterdam
- Manuel Gomez Rodriguez, MPI for Software Systems, Saarbruecken
- David Lopez-Paz, Facebook AI, Paris
- Kun Zhang, Carnegie Mellon University, Pittsburgh
- Alain Hauser, Google
- Alex Peysakhovich, Facebook AI
- Ioannis Tsamardinos, University of Crete
- Antti Hyttinen, University of Helsinki
- Suchi Saria, Johns Hopkins University
---
