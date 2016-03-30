---
title:  "Reinforcement Learning"
layout: workshop
organizer_url: 
categories:
- dali2016
organizers:
- firstname: Csaba
  lastname: Szepesvari
  url: "http://www.ualberta.ca/~szepesva/"
  institute: University of Alberta
- firstname: Yasin 
  lastname: Abbasi-Yadkori
  url: "https://webdocs.cs.ualberta.ca/~abbasiya/"
  institute: Queensland University of Technology
show_abstracts: true
room: "Sala Agave"
talks:
- title: "Information-theoretic policy search for improvement, adaptation and selection of robot motor skills"
  speaker: "Gerhard Neumann"
  start: "09:30"
  end: "10:05"
  abstract: "In this talk, I will focus on reinforcement learning (RL) of robot motor skills where I will concentrate on the sub-problems of skill improvement, skill adaptation and skill selection. I will use a robot table tennis task to illustrate how to solve these challenging learning problems. A big challenge in robot reinforcement learning is that we have to choose the optimal action from a high dimensional continuous action space. Typically, we use parametrized policies with Gaussian noise to implement action selection and exploration in such continuous action domains. Efficient reinforcement learning for motor skills requires to effectively control the exploration-exploitation tradeoff when updating the Gaussian exploration policy through learning. We will derive such policy update using information-theoretic (IT) constraints, i.e., bounding the loss of information and the loss of entropy of the policy update.  Such bounds allow us to effectively control the information-geometric step-sizes for the mean and the covariance of the policy update. Furthermore, we can improve the quality of the policy update by using quadratic approximations of the value function which we will show to be a compatible value function approximation scheme to Gaussian policies. We will implement our IT policy updates for different reinforcement learning algorithms using compatible value function approximation and show their superior performance to existing state of the art. The first RL problem is skill improvement, where we want to optimize a single motion, e.g., a table tennis stroke for a given ball trajectory. We will use a stochastic search formulation, where our policy update is used for a Gaussian search distribution over the parameter space. Subsequently, we extend our approach to skill adaptation. Here, we augment the Gaussian search distribution such the mean of the search distribution depends on the current situation, for example, the estimated trajectory of the incoming ball, and rederive the IT policy updates. As a next step, we want to learn reactive skills that can counteract unpredictable perturbations. We modify our policy update to learn time-dependent feedback controllers, which is equivalent to using the adaptation update at each time step. Finally, I will discuss a new approach for learning when to activate and terminate skills. Inspired by the option framework, which is a well-known tool for temporal abstraction and reusable skills in reinforcement learning, we develop a new algorithm that uses probabilistic inference to learn the sub-policies of each skill, an activation policy that selects the skill to execute and a termination policy that specifies how long the selected skill should be executed. In difference to most other option discovery approaches, our approach is applicable to parametrized policies in the continuous state-action domain, and is therefore well suited for the application in robotics."
- title: "TBA"
  speaker: "Joelle Pineau"
  start: "10:05"
  end: "10:40"
- title: "Adversarial Estimation Methods for Inverse Reinforcement Learning"
  speaker: "Brian Ziebart"
  start: "10:40"
  end: "11:15"
  abstract: "Inverse reinforcement learning attempts to rationalize demonstrated behavior by estimating a reward or cost function that makes observed decision sequences optimal. Unfortunately, this problem is ill-posed in its basic form, admitting only degenerate solutions when learning from noisy data. We present a general framework using adversarial statistical estimation methods to resolve this problem. Maximum entropy inverse optimal control is a special case linking robust causal log loss minimization to a relaxation of the Bellman equation for optimal control. We investigate other loss functions within this adversarial framework to allow better inductive alignment with performance measures and imitation learning settings of practical interest. This is joint work with Xiangli Chen, Mathew Monfort, and Peter Carr."
- title: ""
  start: "Coffee Break"
- title: "Computing Safe Policies with Inaccurate Models"
  speaker: "Marek Petrik"
  start: "11:45"
  end: "12:20"
  abstract: "A fundamental problem in sequential decision-making under uncertainty is to compute a safe policy, i.e., a policy that is guaranteed to have a better performance than a baseline strategy, given a batch of data. In this talk, I describe a model-based approach to this problem, in which the goal is to compute a safe policy, given an inaccurate model of the system with known accuracy guarantees. The inaccurate model and error bound may be constructed using the batch of data and prior knowledge about the system. I first describe a robust optimization problem whose solution is guaranteed to be safe in this setting, and study its main properties: show that it may only have randomized optimal solutions, derive a bound its performance loss, and prove that solving it is NP-hard. I then show several simple approximate solutions to this problem. Joint work with Yinlam Chow and Mohammad Ghavamzadeh"
- title: "Implicit exploration in non-stochastic bandit problems"
  speaker: "Gergely Neu"
  start: "12:20"
  end: "12:55"
  abstract: "In stochastic bandit problems, the principle of "optimism in the face of uncertainty" has proven to be an essential tool for designing efficient exploration policies. Despite this success, the notion of optimism has been relatively unexplored in the world of non-stochastic (or adversarial) bandits. In this talk, I describe an optimistic exploration technique called "implicit exploration" for non-stochastic multi-armed bandits that leads to a family of learning algorithms with improved empirical performance and theoretical guarantees. For the first time, these results suggest that a certain degree of optimism can be very useful even in adversarial domains."
- title: ""
  start: "Lunch and Afternoon Activities"
- title: "Optimising the Confidence Level for Multi-Armed Bandit Algorithms"
  speaker: "Tor Lattimore"
  start: "18:00"
  end: "18:40"
  abstract: "I will present the Optimally Confident UCB algorithm for finite-armed bandits. The new algorithm is simple, efficient, empirically superb and comes with the strongest available theoretical guarantees for the subgaussian noise model. The main idea is that the confidence level should depend on the unknown risk of choosing a sub-optimal arm linearly often. Other algorithms are either too conservative (UCB) or not conservative enough (MOSS). The technical report may be found at http://arxiv.org/abs/1507.07880."
- title: "New algorithms for continual option construction"
  speaker: "Doina Precup"
  start: "18:40"
  end: "19:20"
  abstract: "Temporal abstraction has long been recognized as key to scaling up learning and planning in reinforcement learning. While planning with temporally extended actions is well understood, learning such abstractions autonomously has remained challenging. In this talk, I will present new ideas for learning temporal abstractions autonomously from data in the framework of options. First, I will discuss the idea of using bounded rationality as a lens through which we can describe the desiderata for constructing options, as their goal is mainly to help agents which are restricted in terms of computation time. Using this perspective helps us to formulate objective optimization criteria that should be fulfilled during option construction, which combine naturally with the usual discounted return optimization. I will then describe a policy-gradient approach capable of learning both the internal policies and termination condition of options, in parallel with the policy over options. I will conclude with promising empirical results on several problems. This is joint work with my PhD student Pierre-Luc Bacon"
- title: "Discussion"
  start: "19:20"
  end: "20:00"
- title: ""
  start: "Dinner"
speakers:
- Mohammad Ghavamzadeh
- Gergely Neu
- Gerhard Neumann
- Tor Lattimore
- Marek Petrik
- Joelle Pineau
- Doina Precup
- Martin Riedmiller
- Brian Ziebart
---
