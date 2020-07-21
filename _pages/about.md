---
permalink: /
title: "Research"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a condensed matter physicist. In my research I rely on a variety of theoretical and computational tools such as variational approaches, machine learning, and statistical theory. Condensed matter physics involves the study of large numbers of electrons and nuclei that interact with each other according to a fixed set of simple rules known as quantum mechanics, and which account for a plethora of various phenomena. Starting from these rules, I develop and implement novel methods that can used to simulate the behaviour particular condensed matter systems, with emphasis on realistic materials. 

## Machine Learning 

As opposed to being composed by a set of logical instructions, a machine learning algorithm automatically learns and improves its performance directly from experience. In recent years there has been a surge in the interest of deep neural networks, mainly driven by the availability of data and improvements the ability to train the machine learning models. The connection between machine learning and physics has a long history. Fundamental concepts in physics, such as the concept of energy, has a natural meaning in machine learning such as the loss landscape. Despite of its success, a coherent "theory of machine learning" is still amiss. 

## Quantum Complexity

Arguments from complexity theory suggest that quantum mechanics is vastly superior to classical mechanics from a computational point of view. The existence of Shor’s famous integer factorization algorithm supports a common assumption, namely that all problems that can be solved efficiently on a classical computer can be solved at least as efficiently on a quantum computer, while the opposite might not be true. The realization of general purpose quantum computers has the potential to transform multiple sectors such as finance, security, and logistics. The need for scalability requires a high degree of computational fault-tolerance. Using tools from statistical learning theory and machine learning I develop methods to improve the accuracy of quantum computers. 

## Functional Theories

Solving the quantum-mechanical equations of motion is a computational problem of exponential complexity. A number of approaches known as functional theories has been suggested to adress this problem. One of the most promiment examples is the seminal work by Hohenberg and Kohn. They provided a formal way to map the interacting many-body problem to a variational problem solely formulated in the fermionic particle density. While this strategy results in a significant reduction in computational complexity, a major challenge is to viably include the exchange-correlaton effects in the functionanal approximations. 

## Numerical Simulation of Realistic Materials

The accurate prediction of the properties of materials requires solutions to the Schrödinger equation. We develop a real space code to numerically solve for the electronic density in general materials. We base our solver on the finite element method that allows us construct systematically accurate solutions to the variational Thomas-Fermi equation and its generalizations. The solver handles various kinds of boundary conditions, such as the Dirichlet condition, for general unit cells. 

# Past Research 

### Modeling of high-temperature paramagnetism in disordered systems

The first-principles modeling of the high-temperature paramagnetic state in disordered systems is a profound challenge in condensed matter physics. The origins of this challenge originats in the complex interplay between the nuclear and electronic degrees of freedom. In this work we suggest a novel approach to deal with this problem. By mapping the degrees of freedom onto classical spin Hamiltonian models, we use a direct-cluster averaging method that allows for the accurate and direct computation of the magnetic spin interactions, hence indirectly including the inherent magneto-lattice coupling effects. The method allows for the treatment of general systems with no underlying crystal symmetry and arbitrary degrees of chemical and topological disorder. 

### Semiclassical Origins of Functional Theories 

One of the earliest density-based variational approaches is Thomas-Fermi theory. It becomes exact in certain asymptotic limits. In this work we set out to investigate the kinetic properties of the electronic density in systems with electronic edges. The presence of classical turning points in a many-electron system leads to the breakdown of the extended Thomas-Fermi theory and introduces quantum oscillations in the kinetic energy density in the large N fermionic particle limit. We provide numerical proof of the universal validity of a generalized gradient expansion to closed and semi-inifinite systems under a set of minimal general constraints and discuss its non-uniqueness in some circumstances.  

### Machine Learning Physics 

Machine learning is on the verge of transforming condensed matter physics research and materials science. A most fundamental property of any given material is its thermodynamic stability. We develop several physics-informed machine learning models based on kernel ridge regression that allows for the accurate prediction of the formation energies of general solids. Our models are centered around the inherent property of space group symmetry of the underlying crystal structure, which allows us to omit any coordinate dependence of the descriptor. Given sufficient training, our models allow for arbitrary accuracy. 



