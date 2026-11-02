---
title: 'Kettle: Short Post-Quantum Threshold Signatures from the HAWK Signature Scheme'
collection: publications
date: 2026-10-03
preprint: true
authors:
  - 'Calvin Abou Haidar'
  - 'Daniel Escudero'
  - 'Thomas Espitau'
  - 'Clément Hoffmann'
  - 'Kaoru Takemure'
  - 'Mehdi Tibouchi'
  - 'Hernán Darío Vanegas Madrigal'
eprint: 'https://eprint.iacr.org/2026/2288'
code: 'https://github.com/hdvanegasm/kettle'
abstract: 'HAWK is a lattice-based hash-and-sign signature scheme that was a third round candidate in the NIST additional call for post-quantum signatures. It has short signatures and keys, as well as fast and portable signing and verification. However, in response to a highly-publicized AI-driven cryptanalytic result that reduced its security (roughly doubling the required dimension to achieve a given security level), the authors decided to withdraw from the competition. The need to increase parameters was seen as limiting the size advantage of HAWK compared to the already selected lattice schemes ML-DSA and Falcon, which was one of its primary selling points alongside speed and the lack of floating-point arithmetic. In this paper, we identify another attractive aspect of the HAWK design that is not affected by the AI attack and has been overlooked so far: its surprising friendliness to multi-party computation (MPC). Indeed, HAWK signing can be achieved in a generic way from a small collection of basic composable MPC functionalities (like integer multiplication, uniform random generation, etc.) in such a way that instantiating those functionalities using MPC protocols with given security properties (semi-honest vs. malicious, honest vs. dishonest majority, etc.) yields a secure protocol for MPC signing with those same properties. As a result, we obtain Kettle, a UC-secure threshold signature protocol that outputs specification-compliant HAWK signatures and scales to an arbitrary number of parties. It offers essentially the shortest signature size so far for a lattice-based threshold signature, while achieving significantly lower round complexity and online communication cost than other threshold protocols built from pre-existing, non-threshold lattice-based signatures (like ML-DSA and Falcon): as low as 2 online rounds (a dozen rounds total) and 2 kB online communication per party, depending on the specific setting and optimization choices. We also provide a proof-of-concept implementation of our approach in the MP-SPDZ framework, which can be instantiated with any number of parties, any threshold, and a variety of security properties.'
---
