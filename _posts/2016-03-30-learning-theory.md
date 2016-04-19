---
title:  "Learning Theory"
layout: multitrack
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
room: "Sala Ginestra"
talks:
- title: "How far are we from having a satisfactory theory of clustering?"
  speaker: "Shai Ben-David, Universitys of Waterloo"
  start: "09:30"
  end: "10:05"
  abstract: "Unsupervised learning, taking advantage of huge amounts of raw data available, is widely recognized as one of the most important challenges facing machine learning nowadays. For supervised tasks, machine learning theory has been successful in several respects; providing significant understanding of machine learning tasks (in terms of the resources and tools required to address them), insights about the pros and cons of alternative learning paradigms and their parameter settings, and initiating the development of new algorithmic approaches. However, no such successes had been so far achieved in the unsupervised ML domain. I will focus on clustering and discuss two aspects in which theory could be of great use. The first is model selection - how should a user pick an appropriate clustering tool for a given clustering problem and tune up the parameters it requires? The second aspect I will address is the computational complexity of clustering. Once a clustering model (or objective) has been picked, the task becomes an optimization problem. While most of the clustering objective optimization problems are computationally infeasible, they are being carried routinely in practice. I will describe some of the recent attempts to understand this discrepancy."
- title: "Analysis of Nystrom Method with Sequential Ridge Leverage Score Sampling"
  speaker: "Alessandro Lazaric, INRIA Lille - Nord Europe"
  start: "10:05"
  end: "10:40"
  abstract: "Large-scale kernel ridge regression (KRR) is limited by the need to store a large kernel matrix K_t. To avoid storing the entire matrix K_t, Nystrom methods subsample a subset of columns of the kernel matrix, and efficiently find an approximate KRR solution on the reconstructed kernel matrix. The chosen subsampling  distribution in turn affects the statistical and computational tradeoffs. For KRR problems (Rudi et al., 2015; Alaoui and M. Mahoney, 2015) show that a sampling distribution proportional to the \emph{ridge leverage scores} (RLSs) provides strong reconstruction guarantees for the approximated kernel. While exact RLSs are as difficult to compute as a KRR solution, we may be able to approximate them well enough. In this paper, we study KRR problems in a sequential setting and introduce the INK-Estimate algorithm, that incrementally computes the RLSs estimates. INK Estimate maintains a small sketch of K_t, that at each step is used to compute an intermediate estimate of the RLSs. First, our sketch update does not require access to previously seen columns, and therefore a single pass over the kernel matrix is sufficient. Second, the algorithm requires a fixed, small space budget to run dependent only on the effective dimension of the kernel matrix. Finally, our sketch provides strong approximation guarantees on the reconstruction error, and on the statistical risk of the approximate KRR solution at any time, because all our guarantees hold at any intermediate step."
- title: "Is adaptive early stopping possible in statistical inverse problems?"
  speaker: "Gilles Blanchard, University of Potsdam"
  start: "10:40"
  end: "11:15"
  abstract: "(Joint work with M. Hoffmann and M. Reiss) We consider a standard setting of statistical inverse problem, taking the form of the Gaussian sequence model with D observed noisy coefficients. Consider the simple family of ”keep or kill” estimators depending on a cutoff index k_0. For the choice of the cutoff index, there exist a number of well-known methods achieving oracle adaptivity (i.e. data-dependent choice of k_0 whose performance is comparable to the unknown optimal one), such as penalization and Lepski’s method. However, they have in common that the estimators for all values of k_0 have to be computed first and compared to each other in some way. Contrast this to an ”early stopping” approach where we would like to compute iteratively the estimators for k_0= 1, 2, . . . and have to decide to stop at some point without being allowed to compute the following estimators. Is oracle adaptivity possible then? This question is motivated by settings where computing estimators for larger k_0 requires more computational cost; furthermore some form of early stopping is most often used in practice. We propose a precise mathematical formulation of this question and provide upper and lower bounds on what is achievable."
- title: ""
  start: "Coffee Break"
- title: " Sharp Analysis of Random Feature Expansions"
  speaker: "Francis Bach, Centre de Recherche INRIA de Paris"
  start: "11:45"
  end: "12:20"
  abstract: "Random feature expansions provide a simple way to avoid the usual quadratic running-time complexity of kernel methods. In this talk, I will present recent results about the approximation properties of these expansions. In particular, I will provide improved bounds on the number of features needed for a given approximation quality. I will also draw links with the problem of approximating integrals from finite sums, that is, the kernel quadrature problem."
- title: "Efficient Second Order Online Learning via Sketching"
  speaker: "Haipeng Luo, Princeton University"
  start: "12:20"
  end: "13:00"
  abstract: "We propose Sketched Online Newton (SON), an online second order learning algorithm that enjoys substantially improved regret guarantees for ill-conditioned data. SON is an enhanced version of the Online Newton Step, which, via sketching techniques enjoys a linear running time. We further improve the computational complexity to linear in the number of nonzero entries by creating sparse forms of the sketching methods (such as Oja's rule) for top eigenvector extraction. Together, these algorithms eliminate all computational obstacles in previous second order online learning approaches. This is joint work with Alekh Agarwal, Nicolo Cesa-Bianchi and John Langford."
- title: ""
  start: "Lunch and Afternoon Activities"
- title: "Spectral convergence of the graph Laplacian"
  speaker: "Matthias Hein, Saarland University"
  start: "18:00"
  end: "18:40"
- title: "Bounding the complexity of composite function classes"
  speaker: "Andreas Maurer, Stemmer Imaging"
  start: "18:40"
  end: "19:20"
  abstract: "The current interest in deep learning motivates the search for methods to analyze the complexity of layered function classes. The talk presents a general bound on the Gaussian complexity of the composition of vector-valued function classes in terms of  the complexities of the respective components. Applications exhibit the benefits of implicit feature learning in layered models of multi-task learning."
- title: "Compressive Learning: Projections, Learning, and Sparsity for Efficient Data Processing"
  speaker: "Rémi Gribonval, Centre de Recherche INRIA Rennes - Bretagne Atlantique, France
"
  start: "19:20"
  end: "20:00"
  abstract: "The talk will discuss generalizations of sparse recovery guarantees and compressive sensing to the context of machine learning. Assuming some low-dimensional model on the probability distribution of the data, we will see that in certain scenarios it is indeed possible to (randomly) compress a large data- collection into a reduced representation, of size driven by the complexity of the learning task, while preserving the essential information necessary to process it. Two case studies will be given: compressive clustering, and compressive Gaussian Mixture Model estimation, with an illustration on large-scale model-based speaker verification."
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
