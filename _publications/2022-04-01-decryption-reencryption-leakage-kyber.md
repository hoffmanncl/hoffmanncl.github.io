---
title: 'Systematic Study of Decryption and Re-encryption Leakage: The Case of Kyber'
collection: publications
date: 2022-04-01
venue: 'COSADE 2022'
authors:
  - 'Melissa Azouaoui'
  - 'Olivier Bronchain'
  - 'Clément Hoffmann'
  - 'Yulia Kuzovkova'
  - 'Tobias Schneider'
  - 'François-Xavier Standaert'
eprint: 'https://eprint.iacr.org/2022/036'
doi: 'https://doi.org/10.1007/978-3-030-99766-3_11'
abstract: 'The side-channel cryptanalysis of Post-Quantum (PQ) key encapsulation schemes has been a topic of intense activity over the last years. Many attacks have been put forward: Simple Power Analysis (SPAs) against the re-encryption of schemes using the Fujisaki-Okamoto (FO) transform are known to be very powerful; Differential Power Analysis (DPAs) against the decryption are also possible. Yet, to the best of our knowledge, a systematic and quantitative investigation of their impact for designers is still missing. In this paper, we propose to capture these attacks with shortcut formulas in order to compare their respective strength in function of the noise level. Taking the case of Kyber for illustration, we then evaluate the (high) cost of preventing them with masking and the extent to which different parts of an implementation could benefit from varying security levels. We finally discuss tweaks to improve the situation and enable a better leveling of the countermeasures. Our conclusions confirm that current solutions for side-channel secure PQ key encapsulation schemes like Kyber are unlikely to be efficient in low-noise settings without (design or countermeasures) improvements.'
---
