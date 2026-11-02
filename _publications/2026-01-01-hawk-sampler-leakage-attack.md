---
title: 'Practical Leakage Attack on HAWK''s Gaussian Sampler'
collection: publications
date: 2026-01-01
venue: 'SCIS 2026 (non-refereed national symposium)'
authors:
  - 'Calvin Abou Haidar'
  - 'Clément Hoffmann'
abstract: 'In this paper, we present a leakage template attack targeting the post-quantum signature scheme HAWK. Specifically, our attack exploits an implementation flaw within HAWK’s Gaussian sampler. This vulnerability allows us to recover the signs of the sampler’s outputs. We then leverage these recovered signs through an averaging method to successfully identify and extract the secret key. A key challenge is HAWK’s symbreak operation, which modifies the retrieved signs. We introduce a novel trick to effectively carry the attack through this operation. We practically demonstrated this attack using a ChipWhisperer Pro platform against a HAWK implementation running on an Cortex STM32F4 device. To our knowledge, there is currently no efficient and proven way to implement standard countermeasures like masking in order to protect HAWK’s Gaussian sampler from this type of side-channel attacks.'
---
