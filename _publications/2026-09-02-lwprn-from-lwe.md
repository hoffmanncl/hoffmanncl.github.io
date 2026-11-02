---
title: 'Hardness of Learning with Physical Rounding and Noise from Learning With Errors'
collection: publications
date: 2026-09-02
venue: 'CHES 2026'
authors:
  - 'Clément Hoffmann'
  - 'Emeline Repel'
  - 'Adeline Roux-Langlois'
  - 'François-Xavier Standaert'
tches: 'https://doi.org/10.46586/tches.v2026.i3.1056-1079'
abstract: 'The Learning With Physical Rounding (LWPR) problem is a variant of the Learning With Rounding (LWR) problem, where the rounding operation is performed by a physical leakage function (like the Hamming weight function or variants thereof). It has been introduced as a potentially useful building block towards designing cryptographic algorithms with affordable leakage-resilience guarantees. LWPR has direct applications for fresh re-keying schemes in symmetric cryptography, and potential applications for post-quantum encryption and signature schemes relying on hard learning problems. However, for now its hardness has only been evaluated heuristically, thanks to algebraic cryptanalysis. In this paper, we show that a natural generalization of the LWPR problem with noisy samples, which we denote as Learning With Physical Rounding and Noise (LWPRN), is as hard as the Learning With Errors (LWE) problem. This generalization is motivated by the fact that concrete leakage functions are usually affected by a mild level of physical noise. It targets the same applications as LWPR, yet with much stronger confidence given its reduction from a standard mathematical assumption. By combining proof techniques from lattice-based cryptography and statistical concepts used in the side-channel / masking literature, we argue that the level of noise required in our reduction is concretely affordable. Besides, we show that the generalization from LWPR to LWPRN is not only motivated by the goal of obtaining provable security guarantees, since our reduction applies to the serial implementation setting, in which LWPR has been shown insecure.'
---
