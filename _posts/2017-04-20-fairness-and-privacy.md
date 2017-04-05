---
title:  "Fairness and Privacy in Machine Learning"
abstract:  "The advent of machine learning applications in crucial decision-making processes including law, medicine, banking and education raises a number of important issues with technical and societal ramifications. Driven by these concerns, a growing body of research addresses questions related to fairness, bias, privacy and interpretability in machine learning and artificial intelligence. A fundamental problem in this area is devising formal definitions of these concepts that match the intuitions and properties that users expect from a fair/private/unbiased/interpretable system. Among these, fairness and privacy have seen important success in recent years with the proposal and adoption of definitions that can now be used to certify that machine learning algorithms make fair predictions or respect the privacy of the users in the training dataset.
</br>

This workshop will gather experts in fairness and privacy in machine learning with the goal of discussing the latest technical advances in the area. Additionally, the workshop will serve as a platform to highlight application domains with a pressing need for fairness and privacy technologies. The program also includes a panel discussion where speakers and attendees will have a chance to explore the challenges involved in deploying such technologies and brainstorm about the impact that research in these areas will have in our society."
layout: multitrack
organizer_url: 
categories:
- dali2017
organizers:
- given: Isabel 
  family: Valera
  url: "https://people.mpi-sws.org/~ivalera/"
  institute: Max Planck Institute for Software Systems
- given: Borja 
  family: Balle
  url: "http://www.lancaster.ac.uk/~deballep/"
  institute: Lancaster University
room: El Veril
show_abstracts: true
talks:
- title: “Is Interaction Necessary for Distributed Private Learning?”
  speaker: "Abhradeep Guha Thakurta"
  youtube: 
  start: "09:30"
  end: "10:15"
  abstract: "Recent large-scale deployments of differentially private algorithms employ the local model for privacy (sometimes called the randomized response), where data are randomized on individual's devices before being sent to a server that computes approximate, aggregate statistics. The server need not be trusted for privacy, leaving data control in users' hands. For an important class of convex optimization problems (including logistic regression, support vector machines, and the Euclidean median), the best known locally differentially private algorithm are highly interactive. With n users in the protocol, they use n rounds of back and forth communication. The server exchanges messages with each user only once, but must do so in sequence. 
  We ask: how much interaction is necessary to optimize convex functions in the local DP model? We give a new noninteractive algorithm for local, differentially private convex optimization. For 1-dimensional problems, its error matches the error of the interactive solutions, which are optimal. As the dimension grows, however, our algorithm's required sample size grows exponentially with the dimension.  We show that this dependency is necessary for a large family of algorithms (including those in the literature). Finally, we study algorithms that use interaction sparingly. We show that several natural locally DP algorithms-- analogues of gradient descent and the cutting plane method---obtain low error using relatively few rounds."
- title: “A Decentralized and Robust Protocol for Private Averaging over Highly Distributed Data”
  speaker: "Aurelien Bellet"
  youtube: 
  start: "10:15"
  end: "11:00"
  abstract: "We propose a decentralized protocol for a large set of users to privately compute averages over their joint data, which can be used to learn more complex machine learning models. Our protocol can find a solution of arbitrary accuracy, does not rely on a trusted third party and preserves the privacy of users throughout the execution in both the honest-but-curious and malicious adversary models. Furthermore, we design a verification procedure which offers protection against malicious users joining the service with the goal of manipulating the outcome of the algorithm."
- title: “Data mining approaches for discrimination discovery”
  speaker: "Sara Haijan"
  youtube: 
  start: "11:30"
  end: "12:15"
  abstract: "Algorithms and decision making based on Big Data have become pervasive in all aspects of our daily (offline and online) lives. They determine the media we consume, the stories we read, the people we meet, the places we visit, but also whether we get a job, or whether our loan or insurance request is approved. It is therefore of societal and ethical importance to ask whether these algorithms can be discriminative on grounds, such as gender, ethnicity, marital or health status. In this talk, I will present different examples of racial and gender bias in different online and offline services and explain how algorithmic bias occurs even when there is no discrimination intention in the developer of the learning algorithms. Finally, I will introduce the recent data mining approaches for discrimination discovery from the database of historical decision records."  
- title: “Fairness constraints: a mechanism to design fair classifiers”
  speaker: "Manuel Gomez-Rodriguez"
  youtube: 
  start: "12:15"
  end: "13:00"
  abstract: "Algorithmic decision making is ubiquitous across a wide variety of online as well as offline services. However, there is a growing concern that these automated decisions can lead, even in the absence of intent, to a lack of fairness, i.e., their outcomes can disproportionately hurt (or, benefit) particular groups of people sharing one or more sensitive attributes (e.g., race, sex). In this talk, I will introduce a flexible mechanism to design fair classifiers by leveraging  a novel intuitive measure of decision boundary (un)fairness. I will then show that this mechanism can be easily incorporated into the formulation of several well-known margin based classifiers, without increasing their complexity, and it allows for a fine-grained control on the degree of fairness, often at a small cost in terms of accuracy."

   

speakers:
- Abhradeep Guha Thakurta (University of California Santa Cruz)
- Aurelien Bellet (INRIA Lille)
- Manuel Gomez-Rodriguez (Max Planck Institute for Software Systems)
- Marco Gaboardi (University at Buffalo)
- Sara Hajian (Eurecat Technology Center)
---
