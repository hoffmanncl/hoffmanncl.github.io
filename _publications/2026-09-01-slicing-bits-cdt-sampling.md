---
title: 'Slicing Bits and Cutting Costs in CDT Sampling: High-Order Masking of FrodoKEM''s Gaussian Sampler, Revisited'
collection: publications
date: 2026-09-01
venue: 'CHES 2026'
authors:
  - 'Calvin Abou Haidar'
  - 'Thomas Espitau'
  - 'Clément Hoffmann'
  - 'Mehdi Tibouchi'
eprint: 'https://eprint.iacr.org/2026/1363'
tches: 'https://doi.org/10.46586/tches.v2026.i4.549-574'
code: 'https://github.com/hoffmanncl/frodo_cdt_sampler'
abstract: 'FrodoKEM, a key encapsulation mechanism based on the standard (unstructured) LWE assumption, is recommended as a conservative choice for post-quantum key exchange by agencies like BSI and ANSSI. As such, it has garnered substantial attention from an implementation security standpoint. In particular, several papers have looked into masking FrodoKEM, and, like for various other lattice-based cryptosystems, identified the Gaussian sampling operation as a major bottleneck. In FrodoKEM, it is carried out using a CDT-based sampler, which compares a uniformly random value in [0, 1) (with fixed precision) to each of the probabilities in the cumulative distribution table of the target distribution. Two recent works proposed masked gadgets at arbitrary order for that operation: one by Gérard and Guerreau (CASCADE 2026), which simply masks each of the comparisons with the table elements (using a ripple carry adder as the Boolean comparison circuit), and another by Eid et al. (TCHES 2026), that uses a novel approach based on a binary search tree, significantly reducing the number of masked comparisons for larger tables. Eid et al. also choose the Kogge–Stone adder as the basis for their comparison circuit. In this paper, we provide an extensive analysis of the choices and trade-offs involved in masked CDT-based sampling, and propose several optimizations that further improve upon these previous works by a considerable margin. In particular, since FrodoKEM, like almost all the schemes that rely Gaussian sampling, generates hundreds of samples at a time, we find it beneficial to utilize approaches that lend themselves to a high degree of parallelization. This includes bitslicing (with which, importantly, the ripple carry adder has been proved optimal for comparisons), as well as techniques such as the use of algebraic normal form in masked multiplexers. As a result, on an ARM Cortex-M4 STM32F4 target board, our companion implementation in pure C outperforms the hand-crafted assembly of Eid et al. (resp. Gérard–Guerreau) by a factor of around 2 (resp. 7 to 9) at masking order 1. The gap is even larger at higher order: we outperform the higher-order code of Eid et al. (in C with assembly for expensive gadgets) by a factor ranging from 5 at masking order 2 to 9 as masking order 8.'
---
