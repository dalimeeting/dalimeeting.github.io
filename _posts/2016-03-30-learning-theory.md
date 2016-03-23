---
title:  "Learning Theory"
layout: workshop
organizer_url: 
categories:
- dali2016
organizers:
- firstname: Nicolò 
  lastname: Cesa-Bianchi
  url: "http://homes.di.unimi.it/cesa-bianchi/"
  institute: Università degli Studi di Milano 
- firstname: Lorenzo
  lastname: Rosasco
  url: "http://web.mit.edu/lrosasco/www/"
  institute: University of Genova and MIT
show_abstracts: true
talks:
- title: "How far are we from having a satisfactory theory of clustering?"
  speaker: "Shai Ben-David"
  start: "09:30"
  end: "10:05"
  abstract: "Unsupervised learning, taking advantage of huge amounts of raw data available, is widely recognized as one of the most important challenges facing machine learning nowadays. For supervised tasks, machine learning theory has been successful in several respects; providing significant understanding of machine learning tasks (in terms of the resources and tools required to address them), insights about the pros and cons of alternative learning paradigms and their parameter settings, and initiating the development of new algorithmic approaches. However, no such successes had been so far achieved in the unsupervised ML domain. I will focus on clustering and discuss two aspects in which theory could be of great use. The first is model selection - how should a user pick an appropriate clustering tool for a given clustering problem and tune up the parameters it requires? The second aspect I will address is the computational complexity of clustering. Once a clustering model (or objective) has been picked, the task becomes an optimization problem. While most of the clustering objective optimization problems are computationally infeasible, they are being carried routinely in practice. I will describe some of the recent attempts to understand this discrepancy."
- title: "Analysis of Nystrom Method with Sequential Ridge Leverage Score Sampling"
  speaker: "Alessandro Lazaric"
  start: "10:05"
  end: "10:40"
  abstract: "Large-scale kernel ridge regression (KRR) is limited by the need to store a large kernel matrix K_t. To avoid storing the entire matrix K_t, Nystrom methods subsample a subset of columns of the kernel matrix, and efficiently find an approximate KRR solution on the reconstructed kernel matrix. The chosen subsampling  distribution in turn affects the statistical and computational tradeoffs. For KRR problems (Rudi et al., 2015; Alaoui and M. Mahoney, 2015) show that a sampling distribution proportional to the \emph{ridge leverage scores} (RLSs) provides strong reconstruction guarantees for the approximated kernel. While exact RLSs are as difficult to compute as a KRR solution, we may be able to approximate them well enough. In this paper, we study KRR problems in a sequential setting and introduce the INK-Estimate algorithm, that incrementally computes the RLSs estimates. INK Estimate maintains a small sketch of K_t, that at each step is used to compute an intermediate estimate of the RLSs. First, our sketch update does not require access to previously seen columns, and therefore a single pass over the kernel matrix is sufficient. Second, the algorithm requires a fixed, small space budget to run dependent only on the effective dimension of the kernel matrix. Finally, our sketch provides strong approximation guarantees on the reconstruction error, and on the statistical risk of the approximate KRR solution at any time, because all our guarantees hold at any intermediate step."
- title: "Gilles Blanchard"
  start: "10:40"
  end: "11:15"
- title: ""
  start: "Coffee Break"
- title: " Sharp Analysis of Random Feature Expansions"
  speaker: "Francis Bach"
  start: "11:45"
  end: "12:20"
  abstract: "Random feature expansions provide a simple way to avoid the usual quadratic running-time complexity of kernel methods. In this talk, I will present recent results about the approximation properties of these expansions. In particular, I will provide improved bounds on the number of features needed for a given approximation quality. I will also draw links with the problem of approximating integrals from finite sums, that is, the kernel quadrature problem."
- title: "Efficient Second Order Online Learning via Sketching"
  speaker: "Haipeng Luo"
  start: "12:20"
  end: "13:00"
  abstract: "We propose Sketched Online Newton (SON), an online second order learning algorithm that enjoys substantially improved regret guarantees for ill-conditioned data. SON is an enhanced version of the Online Newton Step, which, via sketching techniques enjoys a linear running time. We further improve the computational complexity to linear in the number of nonzero entries by creating sparse forms of the sketching methods (such as Oja's rule) for top eigenvector extraction. Together, these algorithms eliminate all computational obstacles in previous second order online learning approaches. This is joint work with Alekh Agarwal, Nicolo Cesa-Bianchi and John Langford."
- title: ""
  start: "Lunch and Afternoon Activities"
- title: "Matthias Hein"
  start: "18:00"
  end: "18:40"
- title: "Bounding the complexity of composite function classes"
  speaker: "Andreas Maurer"
  start: "18:40"
  end: "19:20"
- title: "Remi Gribonval"
  start: "19:20"
  end: "20:00"
- title: ""
  start: "Dinner"
speakers:
- Francis Bach 
- Gilles Blanchard 
- Remi Gribonval
- Matthias Hein 
- Alessandro Lazaric 
- Haipeng Luo 
- Andreas Maurer 
- Shai Ben-David 
---
