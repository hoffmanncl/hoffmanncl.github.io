---
title: 'Learning with Physical Rounding for Linear and Quadratic Leakage Functions'
collection: publications
date: 2023-08-01
venue: 'CRYPTO 2023'
authors:
  - 'Clément Hoffmann'
  - 'Pierrick Méaux'
  - 'Charles Momin'
  - 'Yann Rotella'
  - 'François-Xavier Standaert'
  - 'Balazs Udvarhelyi'
eprint: 'https://eprint.iacr.org/2025/2226'
doi: 'https://doi.org/10.1007/978-3-031-38548-3_14'
abstract: 'Fresh re-keying is a countermeasure against side-channel analysis where an ephemeral key is derived from a long-term key using a public random value. Popular instances of such schemes rely on key-homomorphic primitives, so that the re-keying process is easy to mask and the rest of the (e.g., block cipher) computations can run with cheaper countermeasures. The main requirement for these schemes to be secure is that the leakages of the ephemeral keys do not allow recovering the long-term key. The Learning with Physical Rounding (LWPR) problem formalizes this security in a practically-relevant model where the adversary can observe noise-free leakages. It can be viewed as a physical version of the Learning With Rounding (LWR) problem, where the rounding is performed by a leakage function and therefore does not have to be computed explicitly. In this paper, we first consolidate the intuition that LWPR cannot be secure in a serial implementation context without additional countermeasures (like shuffling), due to attacks exploiting worst-case leakages that can be mounted with practical data complexity. We then extend the understanding of LWPR in a parallel implementation setting. On the one hand, we generalize its robustness against cryptanalysis taking advantage of any (i.e., not only worst-case) leakage. A previous work claimed security in the specific context of a Hamming weight leakage function. We clarify necessary conditions to maintain this guarantee, based on the degree of the leakage function and the accuracy of its coefficients. On the other hand, we show that parallelism inherently provides good security against attacks exploiting worst-case leakages. We finally confirm the practical relevance of these findings by validating our assumptions experimentally for an exemplary implementation.'
---
