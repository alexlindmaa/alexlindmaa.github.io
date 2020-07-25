---
permalink: /
title: "Research"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a researcher working in the field of condensed matter physics. I use a variety of theoretical and computational tools such as variational approaches, machine learning, and statistical mechanics to study the nature of complex systems. Condensed matter physics involves the study of large numbers of electrons and nuclei that interact with each other according to a fixed set of rules known as quantum mechanics. Taking these rules as a starting point, I develop and implement novel methods with the goal of simulating the behaviour of realistic material. 

## Machine Learning and Physics

As opposed to being composed by a set of logical instructions, a machine learning algorithm automatically learns from and improves its performance direct from experience. Recent years have witnessed a surge in the broad utility of machine learning modelsm, most notably deep artifical neural networks. These developments have in large parts been driven by the availability of data, the improvements in hardware and software, as well as new ways to efficiently train the machine learning models. The connection between machine learning and physics has a long history. Fundamental concepts in physics, such as the concept of energy, has a natural meaning in machine learning, an example being the loss landscape. Despite of its success, a coherent theory of deep learning is still amiss. The goal of my research is to improve the unerstanding of machine learning models using well known concepts and tools from physics. 

## Quantum Complexity Theory

Arguments from complexity theory suggest that quantum mechanics is vastly superior to classical mechanics from a computational point of view. The existence of Shor’s famous integer factorization algorithm supports a common assumption, namely that all problems that can be solved efficiently on a classical computer can be solved at least as efficiently on a quantum computer, while the opposite is not always the case. The realization of general purpose quantum computers has the potential to transform multiple sectors such as finance, security, and logistics. The apparent need for scalable realizations require a high degree of operational fault-tolerance. Using tools from statistical learning theory and machine learning I develop methods to improve the overall accuracy of quantum computers. 

## Functional Theories

Solving the quantum-mechanical equations of motion requires exponential computational complexity. A number of approaches known as functional theories has been suggested to adress this problem. Among the most promiment examples in this direction is the seminal work by Hohenberg and Kohn, discovred in the 1960's. They provided a formal way to map the interacting many-body problem to a variational problem solely formulated in the fermionic particle density. While this strategy results in a significant reduction in computational complexity, a major challenge is to viably include the exchange-correlaton effects in the functionanal approximations. I am interested in developing new computational schemes that adress this problem on aa general level. 

## Numerical Simulation of Realistic Materials

The accurate prediction of the properties of materials requires solutions to the Schrödinger equation. We have developed a real space code to numerically solve for the electronic particle density in general materials. Our solver is based on the finite element method that allows us to efficiently construct systematic high-accurcy solutions to the variational Thomas-Fermi equation and its generalizations. The solver handles various kinds of boundary conditions, such as the Dirichlet condition, for general unit cells and finite systems. 

# Past Projects

### Computational Modeling of the High-Temperature Paramagnetic State in Disordered Materials

The first-principles modeling of the high-temperature paramagnetic state in disordered systems is a profound challenge in condensed matter physics. The origins of this challenge originats in the complex interplay between the nuclear and electronic degrees of freedom. In this work we suggest a novel approach to deal with this problem. By mapping the degrees of freedom onto classical spin Hamiltonian models, we use a direct-cluster averaging method that allows for the accurate and direct computation of the magnetic spin interactions, hence indirectly including the inherent magneto-lattice coupling effects. The method allows for the treatment of general systems with no underlying crystal symmetry and arbitrary degrees of chemical and topological disorder. 

### Semiclassical Origins of Functional Theories 

One of the earliest density-based variational approaches is Thomas-Fermi theory. Lieb and Simon showed that this theory becomes exact in the infinite particle limit. In this work we set out to investigate the kinetic properties of the electronic density in large systems with electronic edges. The presence of classical turning points in a many-electron system leads to the breakdown of the extended Thomas-Fermi theory and introduces quantum oscillations in the kinetic energy density in the large N fermionic particle limit. We provide numerical proof of the universal validity of a generalized gradient expansion to closed and semi-inifinite systems under a set of minimal general constraints and discuss its non-uniqueness under some circumstances. 

### Machine Learning Physics 

Machine learning is on the verge of transforming condensed matter physics research and materials science. A fundamental question to ask about any material system whether it is stable or not. In this work we developed several physics-informed machine learning models based on kernel ridge regression that allows for the accurate prediction of the formation energies of general solids. Our models are centered around the inherent properties of space group symmetry of the underlying crystal structure, which allows us to omit any coordinate dependence of the descriptor. Given sufficient training, our models allow for arbitrary accuracy.  

### Non-Local Exchange Physics in Semi-Local Density-Based Theories


