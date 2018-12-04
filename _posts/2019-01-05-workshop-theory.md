---
title:  "Machine Learning Theory"
layout: multitrack
abstract: "TBA" 
organizer_url:
categories:
- dali2019
organizers:
- given: Samory
  family: Kpotufe
  url: https://samory.princeton.edu/
  institute: Princeton University
- given: Ilya
  family: Tolstikhin
  url: http://tolstikhin.org
  institute: Google

room: "TBA"
show_abstracts: true
talks:
- title: "Intro"
  author: 
  - given: 
    family: 
    url: 
    institute: 
  youtube: 
  abstract: 
  start: "08:30"
  end: "08:45" 
- title: "Adaptivity for Regularized Kernel Methods by Lepskii’s Principle"
  author:
  - given: Nicole
    family: Mücke
    url: 
    institute: University of Stuttgart
  youtube: 
  start: "08:45"
  end: "09:30"
  abstract: "We address the problem of adaptivity in the framework of reproducing kernel Hilbert
space (RKHS) regression. More precisely, we analyze estimators arising from a linear
regularization scheme. In practical applications, an important task is to choose
the regularization parameter λ appropriately, i.e. based only on the given data at hand
and independently on unknown structural assumptions on the regression function. An
attractive approach avoiding data-splitting is the Lepskii Principle (LP), also known as
the Balancing Principle is this setting. We show that a modified parameter choice based
on (LP) is minimax optimal adaptive, up to log log(n). A convenient result is the fact that
balancing in L2(nu)-norm, which is easiest, automatically gives optimal balancing in all stronger norms, 
interpolating between L2(nu) and the RKHS. An analogous result is open for other classical approaches 
to data dependent choices of the regularization parameter, e.g. for Hold-Out."
- title: "Principles of Active Learning"
  author:
  - given: Steve
    family: Hanneke
    url: http://www.stevehanneke.com/
    institute: Toyota Technological Instituteat Chicago
  youtube: 
  start: "09:30"
  end: "10:15"
  abstract: "In many machine learning applications, the effort required to manually label the massive data sets necessary to train machine learning systems to a high accuracy presents a major hurdle. One promising approach to reducing the required training sample size is active learning, a technique in which the learning algorithm participates in interactively selecting examples to be labeled for training, in order to focus the human expert's efforts on labeling only informative and non-redundant examples. Active learning holds great potential for dramatically reducing the number of labeled training examples needed for learning. However, despite decades of research on the subject, the most popular active learning algorithms in the applications literature are known to be unreliable and sensitive to violations of modeling assumptions, which has held back the widespread applicability of active learning in practice. At the root of this problem, it seems we have lacked a complete understanding of the basic principles that should underlie the design of good active learning algorithms. Such a situation calls for a careful theoretical approach to the problem.\

In this talk, I will articulate essential principles for the design of effective active learning algorithms, distilled from over a decade of research on the theory of active learning. Moreover, I will describe a general active learning strategy based on these principles, which is provably near-optimal, in the sense that the number of labeled training examples sufficient to achieve a given accuracy guarantee cannot be significantly reduced by any other active learning algorithm. In the process, I will discuss the fundamental trade-offs and general complexity measures intrinsic to the active learning setting, and present formulas expressing the minimum number of labeled examples sufficient and necessary for an optimal active learning algorithm to achieve a given accuracy guarantee."
- title: "TBA"
  author:
  - given: Olivier
    family: Bousquet
    url: https://ai.google/research/people/OlivierBousquet
    institute: Google
  youtube: 
  start: "10:15"
  end: "11:00"
  abstract: "TBA"
- title: Coffee Break
  author:
  - given: 
    family: 
    url: 
    institute: 
  youtube: 
  start: "11:00"
  end: "11:30" 
- title: "Building Algorithms by Playing Games"
  author:
  - given: Jacob
    family: Abernethy
    url: http://web.eecs.umich.edu/~jabernet/
    institute: University of Michigan
  youtube: 
  start: "11:30"
  end: "12:15"
  abstract: "A very popular trick for solving certain types of optimization problems is this: write your objective as the solution of a two-player zero-sum game, endow both players with an appropriate learning algorithm, watch how the opponents compete, and extract an (approximate) solution from the actions/decisions taken by the players throughout the process. This approach is very generic and provides a natural template to produce new and interesting algorithms. I will describe this framework and show how it applies in several scenarios, and describe recent work that draws a connection to the Frank-Wolfe algorithm and Nesterov's Accelerated Gradient Descent."
- title: "The Merits of Models in Continuous Reinforcement Learning"
  author:
  - given: Benjamin
    family: Recht
    url: https://people.eecs.berkeley.edu/~brecht/
    institute: University of California, Berkeley
  youtube:
  start: "12:15"
  end: "13:00"
  abstract: "Classical control theory and machine learning have similar goals: acquire data about the environment, perform a prediction, and use that prediction to positively impact the world. However, the approaches they use are frequently at odds. Controls is the theory of designing complex actions from well-specified models, while machine learning makes intricate, model-free predictions from data alone.  For contemporary autonomous systems, some sort of hybrid may be essential in order to fuse and process the vast amounts of sensor data recorded into timely, agile, and safe decisions.\

In this talk, I will examine the relative merits of model-based and model-free methods in data-driven control problems. I will discuss quantitative estimates on the number of measurements required to achieve a high quality control performance and statistical techniques that can distinguish the relative power of different methods. In particular, I will show that model-free methods are considerably less sample efficient than their model-based counterparts. I will further also describe how notions of robustness, safety, constraint satisfaction, and exploration can be transparently incorporated in model-based methods. I will conclude with a discussion of possible positive roles for model-free methods in contemporary autonomous systems that may mitigate their high sample complexity and lack of reliability and versatility."
- title: Lunch
  author:
  - given:
    family:
    url:
    institute:
  youtube:
  start: "13:00"
  end: "15:00"
- title: "A Universally Consistent 1-Nearest-Neighbor Learner"
  author:
  - given: Sivan
    family: Sabato
    url: https://www.cs.bgu.ac.il/~sabatos/
    institute: Ben-Gurion University of the Negev
  youtube: 
  start: "15:00"
  end: "15:45"
- title: "On How Well Generative Adversarial Networks Learn Densities: Nonparametric/Parametric Results, and Pair Regularization"
  author:
  - given: Tengyuan
    family: Liang
    url: http://faculty.chicagobooth.edu/Tengyuan.Liang/
    institute: University of Chicago
  youtube: 
  start: "15:45"
  end: "16:30"
  abstract: "We study in this paper the rate of convergence for learning distributions with the Generative Adversarial Networks (GAN) framework, which subsumes Wasserstein, Sobolev and MMD GANs as special cases. We study a wide range of parametric and nonparametric target distributions, under a collection of objective evaluation metrics. On the nonparametric end, we investigate the minimax optimal rates and fundamental difficulty of the density estimation under the adversarial framework. On the parametric end, we establish theory for neural network classes, that characterizes the interplay between the choice of generator and discriminator. We investigate how to improve the GAN framework with better theoretical guarantee through the lens of regularization. We discover and isolate a new notion of regularization, called the extit{generator/discriminator pair regularization}, that sheds light on the advantage of GAN compared to classic parametric and nonparametric approaches for density estimation."
- title: "Minimax Estimation of Quadratic Fourier Functionals"
  author:
  - given: Bharath K
    family: Sriperumbudur
    url: http://personal.psu.edu/bks18/
    institute: Pennsylvania State University
  youtube: 
  start: "16:30" 
  end: "17:15"
  abstract: "We study estimation of (semi-)inner products between two nonparametric probability distributions, given IID samples from each distribution. These products include relatively well-studied classical L^2 and Sobolev inner products, as well as those induced by translation-invariant reproducing kernels, for which we believe our results are the first. We first propose estimators for these quantities, and the induced (semi)norms and (pseudo)metrics. We then prove non-asymptotic upper bounds on their mean squared error, in terms of weights both of the inner product and of the two distributions, in the Fourier basis. Finally, we prove minimax lower bounds that imply rate-optimality of the proposed estimators over Fourier ellipsoids."

---
