---
title:  "Goals and Principles of Representation Learning"
layout: multitrack
abstract: "Deep learning has driven a revolution in several areas of machine
learning, thanks to a large degree to their ability to discover rich
and useful representations from data. Despite these empirical
successes, especially in supervised learning, significant open
questions remain about the computational goal of unsupervised and
semi-supervised representation learning.

How can we characterise the goal of unsupervised representation
learning? What criteria should one use to evaluate and compare
different data representations? Are maximum likelihood, variational
inference, information bottleneck or hierarchical Bayesian models
fundamentally fit for this purpose and if so, why? Is representation
learning a fundamental problem, or an epiphenomenon of other perhaps
more fundamental tasks, such as transfer learning and data-efficiency.
The goal of this workshop is to explore the recent efforts in
representation learning related, such as disentangling factors of
variation, manifold learning, and transfer learning; the role of prior
knowledge, structure, sparsity, invariances, and smoothness; and  and
the role of representation in problems in reinforcement learning,
natural language, and scene understanding. We shall bring together
machine learning researchers with different views on these questions
to stimulate further discussion and progress."
organizer_url: 
categories:
- dali2018
organizers:
- given: Shakir  
  family:  Mohammed
  url: http://shakirm.com/
  institute: DeepMind
- given: Ferenc  
  family:  Husz&aacuter
  url: http://www.inference.vc/
  institute: Twitter
- given: Andriy   
  family:  Mnih
  url: https://www.cs.toronto.edu/~amnih/
  institute: DeepMind
- given: Lucas   
  family:  Theis
  url: http://theis.io/
  institute: Twitter
room: "Teatro del Mar"
show_abstracts: false
talks:
- title: 
- title: Opening remarks
  author:
  - given: Ferenc
    family: Husz&aacuter
    url: http://www.inference.vc
    institute: Twitter
  youtube: 
  start: "09:30"
  end: "09:55" 
- title: "Inference, relevance and statistical structure: the constraints for useful representations"
  author:
  - given: Harri
    family: Valpola
    url: http://valpola.kapsi.fi/research/
    institute: Curious AI
  youtube: 
  start: "09:55"
  end: "10:30" 
  abstract: "I will argue that representations are there to make useful computations needed for decision making practical. In principle, Bayesian decision theory gives the recipe for deriving optimal decisions given observations and a model class. Also, the golden standard is to select a maximally expressive model class and uninformative prior such as the one derived from Kolmogorov complexity. With infinite computational resources, this would be a recipe for a super intelligence which didn't have any need for representations as we understand them. In practice, though, we are restricted by computational resources. I will give examples of how the need to focus computational resources on relevant inferences creates a pressure to develop useful representations."
- title: "Symbolic representation learning"
  author:
  - given: Marta
    family: Garnelo
    url: https://www.doc.ic.ac.uk/~mg4413/
    institute: Imperial College London
  youtube: 
  start: "10:30"
  end: "11:00" 
  abstract: "A remarkable property of deep learning algorithms is their ability to learn useful task-specific representations from data directly without the need for hand-crafted feature engineering. As they have grown in popularity over the past decade deep neural networks (NNs) have been successfully applied to a wide range of machine learning tasks, achieving state of the art results across many research areas. However, as the complexity of the research problems increase some of the limitations of NN become increasingly clear: NNs suffer from interpretability issues, poor generalisation that leads to very data-hungry algorithms and the inability to be combined with other old, well established AI algorithms. Some of the research tackling these drawbacks takes inspiration from symbolic AI. It focusses, for example, on obtaining interpretable representations from NNs or thinking about objects and relations when building network architectures. This talk reviews symbolic approaches and properties that might be interesting to keep in the back of our heads for current representation learning and reviews current research that merges deep and symbolic methods."
- title: Coffee
  start: "11:00"
  end: "11:30"
- title: "Possible formalizations of Representation Learning"
  author: 
  - given: Olivier
    family: Bousquet
    url: https://research.google.com/pubs/OlivierBousquet.html
    institute: Google Brain
  youtube: 
  start: "11:30"
  end: "12:00" 
  abstract: "While Representation Learning has been discussed for a while and lots of algorithms exist for \"learning representations\", there is no formal definition of what exactly is a representation and what representation learning actually means. This talk will try and review existing approaches in order to identify some organizing principles and propose more precise notions. The goal being to provide a framework in which one can study questions such as \"when does unlabeled data help?\", or \"is this representation transferable?.\""
- title: "Supervised Learning of Rules for Unsupervised Representation Learning"
  author: 
  - given: Jascha
    family: Sohl-Dickstein
    url: http://www.sohldickstein.com
    institute: Google Brain
  youtube: 
  start: "12:00"
  end: "12:30" 
  abstract: "We hypothesize that the limited success of unsupervised representation learning is due to objective function mismatch. Existing approaches to unsupervised representation learning minimize a surrogate objective, such as reconstruction error or the likelihood of a generative model, with the hope that representations useful for subsequent tasks will arise purely as a side effect. As an alternative, we propose using meta-learning to learn, rather than hand-design, an unsupervised learning rule. This meta-learning can be performed with a meta-objective that directly rewards the usefulness of the resulting unsupervised representations for subsequent tasks. We will describe a specific meta-learning architecture, and show that the resulting unsupervised learning rule generalizes across both datasets and data-modalities, and outperforms some existing approaches to unsupervised representation learning."
- title: "Unsupervised Disentanglement or How to Transfer Skills and Imagine Things"
  author: 
  - given: Irina
    family: Higgins
    url: 
    institute: DeepMind
  youtube: 
  start: "12:30"
  end: "13:00" 
  abstract: "Despite the advances in modern deep learning approaches, we are still quite far from the generality, robustness and data efficiency of biological intelligence. We suggest that this gap may be narrowed by re-focusing from implicit representation learning prevalent in end-to-end deep learning approaches to explicit unsupervised representation learning. In particular, we will demonstrate the value of disentangled visual representations acquired in an unsupervised manner loosely inspired by biological intelligence. We will demonstrate how such representations enable the acquisition of reinforcement learning (RL) policies that are more robust to transfer scenarios that standard RL approaches; and form the foundation for learning abstract compositional visual concepts which enable imagination of meaningful and diverse samples beyond the training data distribution."
- title: Break
  start: "13:00"
  end: "18:00"
- title: "Neural decision making in human and machine vision"
  author:
  - given: Matthias
    family: Bethge
    url: http://bethgelab.org
    institute: University of Tübingen
  youtube: 
  start: "18:00"
  end: "18:30"
  abstract: "Understanding how decisions are formed is crucial to improve generalization. Deep learning had impressive successes of feature transfer but due to its distributed nature, decision making in neural networks is difficult to assess. Adversarial examples reveal striking discrepancies between humans and machines but to what extent these discrepancies originate from differences in the architecture or training is not known. In visual decision making humans differ from machines through ubiquitous use of early attentional information selection both due to overt gaze control and covert top-down selection mediated by neural feedback. In this talk, I will present ongoing work of my lab on decision making in CNNs based on constrained architectures and adversarial testing, on modeling human fixation selection, and on incorporating one-shot figure-ground segregation to disentangle object information from clutter."
- title: "Learning Representations for Hyperparameter Transfer Learning"
  author:
  - given: Cedric
    family: Archambeau
    url: http://www0.cs.ucl.ac.uk/staff/c.archambeau/
    institute: Amazon
  youtube: 
  start: "18:30"
  end: "19:00"
  abstract: "Bayesian optimization (BO) is a model-based approach for gradient-free black-box function optimization, such as hyperparameter optimization. In this talk, I will discuss a multi-task adaptive Bayesian linear regression model, whose complexity is linear in the number of function evaluations and able to leverage information of related black-box functions through a shared deep neural net. Experimental results show that the neural net learns a representation suitable for warm-starting related BO runs and that they can be accelerated when the target black-box function (e.g., validation loss) is learned together with other related signals (e.g., training loss).
  Joint work with Valerio Perrone, Rodolphe Jenatton, and Matthias Seeger."
- title: Open Discussion and Debate
  author:
  - given: 
    family:
    url: 
    institute: 
  youtube: 
  start: "18:30"
  end: "19:00"
speakers:
---
