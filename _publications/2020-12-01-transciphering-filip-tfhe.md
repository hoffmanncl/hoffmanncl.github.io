---
title: 'Transciphering, Using FiLIP and TFHE for an Efficient Delegation of Computation'
collection: publications
date: 2020-12-01
venue: 'Indocrypt 2020'
authors:
  - 'Clément Hoffmann'
  - 'Pierrick Méaux'
  - 'Thomas Ricosset'
eprint: 'https://eprint.iacr.org/2020/1373'
doi: 'https://doi.org/10.1007/978-3-030-65277-7_3'
code: 'https://github.com/hoffmanncl/HybridFHE_FiLIP'
abstract: 'Improved filter permutators are designed to build stream ciphers that can be efficiently evaluated homomorphically. So far the transciphering with such ciphers has been implemented with homomorphic schemes from the second generation. In theory the third generation is more adapted for the particular design of these ciphers. In this article we study how suitable it is in practice. We implement the transciphering of different instances of the stream cipher family FiLIP with homomorphic encryption schemes of the third generation using the TFHE library. We focus on two kinds of filter for FiLIP. First we consider the direct sum of monomials, already evaluated using HElib and we show the improvements on these results. Then we focus on the XOR-threshold filter, we develop strategies to efficiently evaluate any symmetric Boolean function in an homomorphic way, allowing us to give the first timings for such filters. We investigate different approaches for the homomorphic evaluation: using the leveled homomorphic scheme TGSW, an hybrid approach combining TGSW and TLWE schemes, and the gate bootstrapping approach. We discuss the costs in time and memory and the impact on delegation of computation of these different approaches, and we perform a comparison with others transciphering schemes.'
---
