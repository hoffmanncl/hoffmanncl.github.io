---
title: 'Towards Case-Optimized Hybrid Homomorphic Encryption: Featuring the Elisabeth Stream Cipher'
collection: publications
date: 2022-12-01
venue: 'Asiacrypt 2022'
authors:
  - 'Orel Cosseron'
  - 'Clément Hoffmann'
  - 'Pierrick Méaux'
  - 'François-Xavier Standaert'
eprint: 'https://eprint.iacr.org/2022/180'
doi: 'https://doi.org/10.1007/978-3-031-22969-5_2'
code: 'https://github.com/princess-elisabeth/'
abstract: 'Hybrid Homomorphic Encryption (HHE) reduces the amount of computation client-side and bandwidth usage in a Fully Homomorphic Encryption (FHE) framework. HHE requires the usage of specific symmetric schemes that can be evaluated homomorphically efficiently. In this paper, we introduce the paradigm of Group Filter Permutator (GFP) as a generalization of the Improved Filter Permutator paradigm introduced by Méaux et al. From this paradigm, we specify Elisabeth, a family of stream cipher and give an instance: Elisabeth-4. After asserting the security of this scheme, we provide a Rust implementation of it and ensure its performance is comparable to state-of-the-art HHE. The true strength of Elisabeth lies in the available operations server-side: while the best HHE applications were limited to a few multiplications server-side, we used data sent through Elisabeth-4 to homomorphically evaluate a neural network inference. Finally, we discuss the improvement and loss between the HHE and the FHE framework and give ideas to build more efficient schemes from the Elisabeth family.'
---
