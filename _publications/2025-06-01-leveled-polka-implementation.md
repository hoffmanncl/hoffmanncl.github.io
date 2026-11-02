---
title: 'Leveled Software Implementation of Polka and Comparison with Uniformly Masked Kyber'
collection: publications
date: 2025-06-01
venue: 'ACNS 2025 Workshops'
authors:
  - 'Thibaud Schoenauen'
  - 'Clément Hoffmann'
  - 'Charles Momin'
  - 'Thomas Peters'
  - 'François-Xavier Standaert'
doi: 'https://doi.org/10.1007/978-3-032-01806-9_6'
pdf: 'https://perso.uclouvain.be/fstandae/PUBLIS/328.pdf'
abstract: 'Polka is a post-quantum public-key encryption scheme from PKC 2023, designed in order to be efficiently protected against side-channel attacks. Its motivation arises from the acknowledged difficulty of protecting Kyber against such attacks. Concretely, the structure of Polka aims to allow so-called leveled implementations, so that protecting its long-term key requires strong and expensive countermeasures (like masking) for a part of its operations only. This contrasts with Kyber, for which preventing side-channel attacks requires to uniformly protect all its operations. The good leakage-resilience features of Polka nevertheless come with performance overheads in an unprotected implementation context. Since no concrete implementations of Polka were proposed so far, it left the question of the number of shares for which it can become an interesting alternative to Kyber open. We bridge this gap by proposing a leveled software implementation of Polka and show that, already for two shares, it leads to significant performance gains over the state-of-the-art uniformly masked implementations of Kyber (Bos et al., TCHES 2021, Bronchain and Cassiers, TCHES 2022).'
---
