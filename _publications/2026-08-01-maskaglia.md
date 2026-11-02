---
title: 'Maskaglia: A New, Efficient Approach to Masked Discrete Gaussian Sampling'
collection: publications
date: 2026-08-01
venue: 'CRYPTO 2026'
authors:
  - 'Calvin Abou Haidar'
  - 'Thomas Espitau'
  - 'Clément Hoffmann'
  - 'Mehdi Tibouchi'
eprint: 'https://eprint.iacr.org/2026/988'
doi: 'https://doi.org/10.1007/978-3-032-35415-0_6'
abstract: 'Discrete Gaussian sampling is an important operation at the core of many lattice-based cryptosystems, which presents significant challenges from an implementation standpoint. In particular, it is difficult to protect against side-channel attacks. Extensive research has gone into the problem of addressing timing side-channel attacks, and as result, constant-time discrete Gaussian sampling is now well-understood. However, few papers so far have attempted to achieve protection against stronger side-channel attacks like correlation power analysis via, e.g., masking, and those that have tend to suffer from underwhelming performance. Focusing on the case of discrete Gaussians with fixed center and standard deviation, the state-of-the-art approach to applying a masking countermeasure is to start from a constant-time cumulative distribution table-based (CDT-based) sampler, possibly with a search tree twist. Such a CDT-based sampler compares a uniform random value to each element of the CDT of the target distribution. Replacing these comparisons with a masked comparison circuit (typically based on a carry-save adder like Kogge–Stone) yields the desired, albeit costly, countermeasure. In this paper, we propose a very different approach to masked discrete Gaussian sampling. We start from a new rejection-based discrete Gaussian sampler, obtained by discretizing a sampler for the continuous normal distribution related to an algorithm of Marsaglia (1963). We show that our new sampler can be expressed elegantly in terms of uniform and geometric distributions, in a way that is surprisingly friendly to masking, particularly when using bitslicing. The resulting masked, t-probing secure gadget dramatically outperforms previous work. When applied to NIST candidate signature Hawk, we find it to need less than 5 masked AND gates per generated sample on a 32-bit architecture, and about 20 times fewer than the state-of-the-art, comparison tree-based masked sampler of Eid et al. (TCHES 2026). Furthermore, we show that while Eid et al.’s sampler can be sped up with significant tweaks (bitslicing, faster masked comparisons, etc.), the modified gadget still requires 4 to 5 times as many masked AND gates as our techniques.'
---
