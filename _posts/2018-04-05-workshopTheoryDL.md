---
title:  "Theory of Deep Learning"
layout: multitrack
abstract: "Over the last years deep learning has developed into one of the most important areas of machine learning leading to breakthroughs in various applied fields like image and natural language processing or machine translation. These numerous advances on practical side are accompanied by a rather limited but growing theoretical understanding. Important questions relating to the representational power of the models, the interpretability of the solutions obtained, the stability and understanding of the stochastic optimization process, the generalization performance of deep neural networks, and new mathematical frameworks to learn generative models - just to name some - require us to delve deeper into the mathematics underlying the field of deep learning. In this workshop we will discuss recent achievements, status quo, and open questions regarding our theoretical understanding of deep learning." 
organizer_url: 
categories:
- dali2018
organizers:
- given: Guido  
  family:  Montufar
  url: http://www.math.ucla.edu/~montufar/
  institute: University of California, Los Angeles 
- given: Asja  
  family:  Fischer
  url: http://sda.cs.uni-bonn.de/people/dr-asja-fischer/
  institute: University of Bonn
room: "Timanfaya"
show_abstracts: true
talks:
- title: "Intro"
  author:
  - given: 
    family: 
    url:
    institute: 
  youtube: 
  abstract: "Abstract here"
  start: "09:20"
  end: "09:30" 
- title: "What could a theory of deep learning look like?"
  author:
  - given: Olivier
    family: Bousquet
    url: https://research.google.com/pubs/OlivierBousquet.html
    institute: Google
  youtube: 
  start: "09:30"
  end: "10:00"
  abstract: "While there is a wide consensus that 'we don't understand Deep Learning' and in particular, we don't understand generalization of Deep Networks, there is not clear consensus of what 'understanding' would even mean in this context. We thus propose to review what we 'understand' about other machine learning algorithms to see if any of that understanding can be transferred to Deep Learning. Also, we will try and frame some of the questions that remained unanswered in as precise a way as possible, so as to contribute to guiding the development of a theory of Deep Learning."
- title: "Expressiveness of ConvNets as a function of Network Architecture"
  author:
  - given: Amnon
    family: Shashua
    url: https://www.cs.huji.ac.il/~shashua/
    institute: Hebrew University of Jerusalem
  youtube: 
  start: "10:00"
  end: "10:30" 
  abstract: "I will go through a series of recent works performed at my lab focusing on the effect of depth, connectivity, pooling geometry, number of channels per layer, size of kernels - in short architectural decisions of a ConvNet design - affects expressivity and inductive bias in a super-linear (mostly exponential) manner."
- title: "Expressivity of Deep Neural Networks"
  author:
  - given: Gitta
    family: Kutyniok
    url: https://www.math.tu-berlin.de/fachgebiete_ag_modnumdiff/angewandtefunktionalanalysis/v_menue/mitarbeiter/kutyniok/v_menue/home/
    institute: TU Berlin 
  youtube: 
  start: "10:30"
  end: "11:00" 
  abstract: "In this talk, we will be concerned with the general question, how well a function can be approximated by a structured neural network such as with sparse connectivity. We will in particular present results on the minimal possible sparse connectivity for a prescribed approximation accuracy, which lead to a construction of memory-optimal neural networks. Moreover, we will discuss a comprehensive approximation theory-driven approach to understand the impact of the depth of a neural network."
- title: Coffee Break
  author:
  - given: 
    family: 
    url: 
    institute: 
  youtube: 
  start: "11:00"
  end: "11:30" 
- title: "Explaining Neural Network Predictions with Deep Taylor Decompositions"
  author:
  - given: Gregoire
    family: Montavon
    url: https://www.ml.tu-berlin.de/menue/members/gregoire_montavon/
    institute: TU Berlin 
  youtube: 
  start: "11:30"
  end: "12:00"
  abstract: "Deep neural networks (DNNs) have been highly successful at extracting complex nonlinear predictive models from large amounts of data. In practical applications, it is important to verify that the high predictive accuracy is reflective of a proper problem representation and not on the exploitation of artefacts in the data. Methods for visualizing and interpreting how the model predicts have therefore received growing attention. 
In this talk, a recently proposed framework for explaining machine learning predictions, deep Taylor decomposition (DTD), will be presented. The framework applies robustly and systematically to complex DNNs. It can be understood as performing a Taylor decomposition at each neuron of the DNN, and recomposing the result of each analysis. In practice, the method is implemented as a backward propagation pass in the DNN. 
Emphasis will be placed on describing peculiarities of the explanation problem, and how the DTD framework relates to them, in particular: (1) global vs. local explanations, (2) explaining function value vs.~function variation, (3) the gradient shattering effect in DNNs, and (4) the need to combine the prediction function and the input domain to produce meaningful explanations."
- title: "Learning in the presence of label noise - Cancelled"
  author:
  - given: Raja
    family: Giryes
    url: http://tam-son3.eng.tau.ac.il/~raja/
    institute: Tel Aviv University
  youtube: 
  start: "12:00"
  end: "12:30" 
  abstract: "Training deep neural networks require a large amount of labeled data. As these labels are generated by human annotators, it may happen that some of the labels are wrongly annotated. Therefore, an important question is how robust are neural networks in training with label noise. In this work, we study the attributes of deep neural networks that make them robust to label noise."
- title: "Nearest Neighbor View of Neural Networks"
  author:
  - given: Gilad 
    family: Cohen
    url: 
    institute: Tel Aviv University
  youtube: 
  start: "12:00"
  end: "12:30" 
  abstract: ""
- title: "Exploring the Geometry of the Latent Space for Variational AutoEncoders"
  author:
  - given: Luigi
    family: Malago
    url: http://www.luigimalago.it
    institute: RIST
  youtube: 
  start: "12:30"
  end: "13:00" 
  abstract: "Variational AutoEncoders are generative models which consist of two parts: an encoder, which maps inputs to the parameters of a probability density function over the latent space, followed by a decoder, which maps latent variables to probability density functions over the observation space. In principle, such models could be trained by optimizing the log-likelihood, however since this would not be computationally efficient, Variational AutoEncoders are usually trained using variational inference approaches, in particular by maximizing a lower-bound for the log-likelihood of the model. The current research in this field covers different directions, such as employing richer models over the latent variables, defining sharper bounds for the loss function, or similarly relating the recognition and generative networks, for instance by sharing parameters. In this presentation we focus our attention on some aspects which are transversal to the previous ones, starting from the characterization of the geometrical properties of the statistical model for the latent variables learned during training. It is well-known that Variational AutoEncoders learn intrinsically sparse models, even if their working mechanisms behave differently from other families of regularized AutoEncoders. In our work we are interested is exploiting the intrinsic properties of the latent model, as well as introducing explicitly in the analysis alternative geometries for the space of statistical models. The purpose of the study it to evaluate the impact of the hyper-parameters of the model over the learned geometry, and at the same time get insights for the design of more robust and efficient training procedures for Variational AutoEncoders."
- title: Lunch
  author:
  - given: 
    family: 
    url: 
    institute: 
  youtube: 
  start: "13:00"
  end: "18:00" 
- title: "Why can Deep Networks avoid the curse of dimensionality and two other theoretical puzzles "
  author:
  - given: Tomaso
    family: Poggio
    url: https://mcgovern.mit.edu/principal-investigators/tomaso-poggio
    institute: MIT
  youtube: 
  start: "18:00"
  end: "18:30" 
  abstract: "A mathematical theory of deep networks and of why they work as well as they do is now emerging. I will review recent theoretical results on the approximation power of deep networks including conditions under which they can be exponentially better than shallow networks. A class of deep convolutional networks represent an important special case of these conditions, though weight sharing is not the main reason for their exponential advantage. I will also discuss two other puzzles associated with deep networks:
* the unreasonable easiness of optimization of the training error;
* the strange lack of overfitting despite large overparametrization in the absence of explicit regularization.
"
- title: "Discussion"
  author:
  - given: 
    family: 
    url:
    institute: 
  youtube: 
  start: "18:45"
  end: "19:15" 
speakers:
---

