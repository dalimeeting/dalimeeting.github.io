---
title:  "The Data Science Process"
abstract:  "This workshop aims to cover the following main topics related to the data process pipeline: </br>  </br> 1) Open challenges in data science: The gap between machine learning techniques and how to apply them in real-world data. Which problems do scientists still face when trying to use ML techniques?
 </br> 2) Collaboration: How do you collaborate on building Machine Learning Models/Systems?
 </br> 3) Automation of Data Science: Current efforts that the ML community is doing to address these challenges. Tools that are being developed to ease the data science process including among others probabilistic programming, automating model selection, automating pipeline construction."
layout: multitrack
organizer_url: 
categories:
- dali2017
organizers:
- given: "Joaquin" 
  family:  "Vanschoren"
  url: http://www.win.tue.nl/~jvanscho/
  institute: "Eindhoven University of Technology"
- given: "Alessya"
  family:  "Labzhinova"
  url: https://www.linkedin.com/in/alessya/
  institute: "Amazon"
room: Caleta
show_abstracts: true
talks:
- title: "Data challenges with modularization and code submission"
  speaker: "Balazs Kegl"
  youtube: 
  start: "09:30"
  end: "10:15"
  abstract: "Motivated by the shortcomings of traditional data challenges, we have developed a unique concept and platform, called Rapid Analytics and Model Prototyping (RAMP), based on modularization and code submission. Open code submission allows participants to build on each other’s ideas, provides the organizers with a fully functioning prototype, and makes it possible to build complex machine learning workflows while keeping the contributions simple. We will start this presentation by describing the context and motivation, the guiding design principles, and some of the technical details (front and backend) of the platform. We will then walk you through some of the most interesting workflows and applications (e.g., anomaly detection in particle physics detectors, classifying molecular spectra for safe drug administration, spatio-temporal time series prediction in climate science). In the last third of the talk we will present a preliminary analysis of the RAMPs that touches on both the technical (machine learning) aspects of the tool and on the sociology of crowdsourcing data analytics."
- title: "Closing the loop in recommender systems"
  speaker: "Jason Gauci"
  youtube: 
  start: "10:15"
  end: "11:00"
  abstract: "In this talk I will walk through a brief history of recommender system implementations in YouTube, iOS Proactive Assistant, and Facebook Newsfeed.  One key challenge in all of these products is that models are learning from a dataset and updating the same dataset simultaneously. I'll discuss a set of issues that arise from these dynamics and ways to address these issues, including an introduction to deep reinforcement learning."
- title: "The Data Science Process"
  speaker: "Neil Lawrence"
  youtube: 
  start: "11:30"
  end: "12:15"
  abstract: "In this talk we will focus on challenges in facilitating the data science pipeline. Drawing on experience from projects in computational biology, the developing world and Amazon I’ll propose different ideas for facilitating the data science process including analogies that help software engineers understand the challenges for data science and formalizations, such as data readiness levels, which allow management to reason about the obstacles in the process."
- title: "OpenML: towards democratizing and automating machine learning"
  speaker: "Joaquin Vanschoren"
  youtube: 
  start: "12:15"
  end: "13:00"
  abstract: "Building machine learning systems remains something of an art, from gathering and transforming the right data to selecting and finetuning the most fitting modeling techniques. If we want to make machine learning more accessible and foster skilfull use, we need novel ways to share and reuse findings, and streamline online collaboration. 
  
  OpenML is an open science platform for machine learning, allowing anyone to easily share data sets, code, and experiments, and collaborate with people all over the world to build better models. It shows, for any known data set, which are the best models, who built them, and how to reproduce and reuse them in different ways. It is readily integrated into several machine learning environments, so that you can share results with the touch of a button or a line of code. As such, it enables large-scale, real-time collaboration, allowing anyone to explore, build on, and contribute to the combined knowledge of the field. 
  
  Ultimately, this provides a wealth of information for a novel, data-driven approach to machine learning, where we learn from millions of previous experiments to either assist people while analyzing data (e.g., which modeling techniques will likely work well and why), or automate the process altogether."
- title: "Towards Automating the Data Analytic Process"
  speaker: "Chris Williams"
  youtube: 
  start: "18:00"
  end: "18:30"
  abstract: "A common view is that up to 80% of work on a data mining project is involved in data understanding and data preparation, yet machine learning has not focussed very much on these topics. In this talk I will describe some challenges and work wrt Data Parsing, Data Understanding, Data Cleaning, Data Integration and Data Restructuring."
- title: "Automatic Discovery of the Statistical Types of Variables in a Dataset"
  speaker: "Isabel Valera"
  youtube: 
  start: "18:30"
  end: "19:00"
  abstract: "A common practice in statistics and machine learning is to assume that the statistical data types (e.g., ordinal, categorical or real-valued) of variables, and usually also the likelihood model, is known. However, as the availability of real-world data increases, this assumption becomes too restrictive. Data are often heterogeneous, complex, and improperly or incompletely documented. Surprisingly, despite their practical importance, there is still a lack of tools to automatically discover the statistical types of, as well as appropriate likelihood (noise) models for,  the variables in a dataset. In this work, we fill this gap by proposing a Bayesian method, which accurately discovers the statistical data types in both synthetic and real  data."
- title: "Causal Impact: estimating the effect of an intervention without user interaction"
  speaker: "Alain Hauser"
  youtube: 
  start: "19:00"
  end: "19:30"
  abstract: "How many additional daily downloads were generated by an advertisement campaign of an app? How many children got additionally vaccinated each month after showing a TV spot advertising vaccination? Randomized experiments are the best way to answer such questions, but often not feasible in practice. The CausalImpact R package (https://google.github.io/CausalImpact/) estimates the effect of an intervention in the absence of a randomized experiment; it uses a Bayesian structural time series model to predict how the response metric would have evolved had the intervention not occurred. CausalImpact can be used in a wide range of different applications without manual tuning thanks to different key features: the default parameter priors facilitate automated fitting of a time series model via variable selection and make domain expertise redundant in many cases; the output is available either in a data structure which is easily processed by software, or in a format which is intelligible to users without formal training in statistics."
- title: "AI assistance for data science via probabilistic programming"
  speaker: "Vikash Mansinghka"
  youtube: 
  start: "19:30"
  end: "20:00"
  abstract: "Demand for data science is rapidly growing. However, many commercial and scientific data sources present fundamental inferential challenges. Examples include the prevalence of mixed data types, convenience samples with tens or hundreds of uncontrolled variables, complex multivariate outcomes, incomplete measurements, coding errors, measurement noise, irrelevant variables, and limited causal knowledge. A key bottleneck is hiring individuals with the necessary education and statistical judgment to address these challenges.

This talk will describe BayesDB, a probabilistic programming platform for AI-assisted data science that has been developed over the last 10 years. Novice BayesDB users can answer data analysis questions in seconds or minutes with a level of rigor that otherwise requires hours or days of work by someone with advanced training in statistics plus good statistical judgment. BayesDB also provides advanced probabilistic programming capabilities that enable experts to integrate causal domain knowledge and black-box machine learning with hierarchical Bayes.

Examples will be drawn from both commercial partnerships and collaborations with philanthropic organizations such as the Bill & Melinda Gates Foundation." 
speakers:
- Balazs Kegl (CNRS - Centre national de la recherche scientifique, Paris-Saclay)
- Jason Gauci (Facebook)
- Neil Lawrence (Amazon)
- Joaquin Vanschoren (Eindhoven University of Technology)
- Chris Williams (University of Edinburgh)
- Isabel Valera (University of Cambridge)
- Alain Hauser (Bern University of Applied Sciences)
- Vikash Mansinghka (Massachusetts Institute of Technology)
---
