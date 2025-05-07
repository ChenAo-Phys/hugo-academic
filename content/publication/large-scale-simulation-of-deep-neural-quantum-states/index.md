---
title: Large-scale simulation of deep neural quantum states
publication_types:
  - "7"
authors:
  - Ao Chen
abstract: >-
  The study of quantum many-body systems remains a central challenge in
  condensed

  matter physics due to the exponential growth of the Hilbert space with system size. Traditional

  numerical approaches, such as exact diagonalization, quantum Monte Carlo, and

  tensor networks, often struggle with respective computational limitations, particularly

  in two and three-dimensional systems with strong correlations. In recent years, deep

  learning has emerged as a powerful alternative, offering new perspectives on quantum

  state representation and simulation. This thesis explores the large-scale simulation of

  deep neural quantum states (NQSs), leveraging artificial neural networks to approximate

  quantum many-body wave functions efficiently.


  We begin by introducing the foundational concepts of NQS and their potential in overcoming

  the curse of dimensionality in quantum many-body problems. Variational Monte

  Carlo (VMC) is employed as the primary optimization framework, allowing the ground-state

  properties of complex Hamiltonians to be explored stochastically. The stochastic

  reconfiguration (SR) and minimum-norm SR (MinSR) are then introduced for accurate

  and efficient optimization of deep NQSs. We further investigate various neural network

  architectures, including feed-forward neural networks, restricted Boltzmann machines,

  convolutional neural networks, and transformer-based wave functions, assessing their expressivity

  and efficiency in encoding quantum correlations in strongly correlated quantum

  matters. The symmetry projection of NQSs starting from the group theory is introduced

  in detail, and particular attention is given to symmetry-preserving network architectures.


  With the help of VMC, MinSR, and symmetry projection, the NQS achieves outstanding

  accuracy and outperforms existing numerical methods in several benchmark models

  of spin systems. We then show its application in quantum spin liquids (QSLs), the study

  of which relies heavily on the advances of computational methods. The NQS provides

  an accurate estimation of phase diagrams and energy gaps of several QSL candidates in

  the square J1-J2 model, the triangular J1-J2 model, and the Shastry-Sutherland model,

  leading to a deeper understanding of the emergence of QSL in frustrated magnets.


  In fermion systems, fermionic mean-field wavefunctions are introduced to combine

  with the NQS for efficient expression of fermion sign structures. We then discuss the

  application of fermionic NQSs in the Fermi-Hubbard model, which reflects the mechanism

  of the Mott-insulator transition and probably high-temperature superconductivity. The

  fermionic NQS successfully reproduces the insulator transition and the spin density wave

  predicted by other numerical methods and further observes the possible superconducting

  order in the Hubbard model.


  These findings highlight the immense potential of deep NQSs in quantum many-body

  physics. By combining large-scale neural networks with variational quantum algorithms,

  we make the NQS a powerful tool in solving quantum many-body systems, paving the

  way for future advancements in the computational study of quantum materials.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2025-05-07T15:42:23.770Z
---
