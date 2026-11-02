---
title: 'Learning Parity with Physical Noise: Imperfections, Reductions and FPGA Prototype'
collection: publications
date: 2021-09-01
venue: 'CHES 2021'
authors:
  - 'Davide Bellizia'
  - 'Clément Hoffmann'
  - 'Dina Kamel'
  - 'Hanlin Liu'
  - 'Pierrick Méaux'
  - 'François-Xavier Standaert'
  - 'Yu Yu'
tches: 'https://doi.org/10.46586/tches.v2021.i3.390-417'
abstract: 'Hard learning problems are important building blocks for the design of various cryptographic functionalities such as authentication protocols and post-quantum public key encryption. The standard implementations of such schemes add some controlled errors to simple (e.g., inner product) computations involving a public challenge and a secret key. Hard physical learning problems formalize the potential gains that could be obtained by leveraging inexact computing to directly generate erroneous samples. While they have good potential for improving the performances and physical security of more conventional samplers when implemented in specialized integrated circuits, it remains unknown whether physical defaults that inevitably occur in their instantiation can lead to security losses, nor whether their implementation can be viable on standard platforms such as FPGAs. We contribute to these questions in the context of the Learning Parity with Physical Noise (LPPN) problem by: (1) exhibiting new (output) data dependencies of the error probabilities that LPPN samples may suffer from; (2) formally showing that LPPN instances with such dependencies are as hard as the standard LPN problem; (3) analyzing an FPGA prototype of LPPN processor that satisfies basic security and performance requirements.'
---
