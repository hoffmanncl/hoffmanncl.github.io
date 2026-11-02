---
title: 'Knuth–Yao Masked Sampling: Improved Performance for FrodoKEM''s and HAWK''s Gaussian Samplers'
collection: publications
date: 2027-01-01
venue: 'CHES 2027'
authors:
  - 'Calvin Abou Haidar'
  - 'Clément Hoffmann'
eprint: 'https://eprint.iacr.org/2026/2287'
code: 'https://github.com/hoffmanncl/knuth_yao_masked_sampler'
abstract: 'Discrete Gaussian sampling remains one of the most delicate operations to protect against side-channel attacks in lattice-based cryptography. In this work, we present the first masked evaluation of the Knuth–Yao sampler. Its random-walk formulation might seem fundamentally at odds with masking, since the walk’s control flow depends precisely on the secret sample being produced. We show instead that its underlying tree structure is remarkably suited to it. Evaluated as a bitsliced Boolean circuit, the public tree prescribes an evaluation order requiring exactly L − 2 masked AND gadgets, where L is the total Hamming weight of the probability expansions of the target distribution, which makes the approach particularly effective for the narrow distributions used in lattice-based schemes. We provide a generic framework that compiles any finite-precision distribution into a masked C implementation with optimized linear-gate count, and instantiate it on all FrodoKEM and Hawk parameter sets. On ARM Cortex-M4, our sampler outperforms the state-of-the-art masked CDT approach for every distribution and masking order, running up to twice as fast at order 1, even for distributions where it evaluates more non-linear gates. Finally, since the Fujisaki–Okamoto transform ties FrodoKEM to the exact randomness consumption of its specified sampler, we discuss the consequences of this constraint. We benchmarked an unmasked implementation and argue that the Knuth–Yao approach is competitive even without masking, while using identical input randomness.'
---
