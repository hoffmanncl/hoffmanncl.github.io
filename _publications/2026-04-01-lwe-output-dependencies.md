---
title: 'Learning with Errors with Output Dependencies: LWE, LWR, and Physical Learning Problems Under the Same Umbrella'
collection: publications
date: 2026-04-01
venue: 'PQCrypto 2026'
authors:
  - 'Clément Hoffmann'
  - 'Pierrick Méaux'
  - 'Mélissa Rossi'
  - 'François-Xavier Standaert'
eprint: 'https://eprint.iacr.org/2025/2225'
doi: 'https://doi.org/10.1007/978-3-032-22695-2_10'
abstract: 'Learning problems have become a foundational element for constructing quantum-resistant cryptographic schemes, finding broad application even beyond, such as in Fully Homomorphic Encryption. The increasing complexity of this field, marked by the rise of physical learning problems due to research into side-channel leakage and secure hardware implementations, underscores the urgent need for a more comprehensive analytical framework capable of encompassing these diverse variants. In response, we introduce Learning With Errors with Output Dependencies (LWE-OD), a novel learning problem defined by an error distribution that depends on the inner product value and therefore on the key. LWE-OD instances are remarkably versatile, generalizing both established theoretical problems like Learning With Errors (LWE) or Learning With Rounding (LWR), and emerging physical problems such as Learning With Physical Rounding (LWPR). Our core contribution is establishing a reduction from LWE to LWE-OD. This is accomplished by leveraging an intermediate problem, denoted qLWE. Our reduction follows a two-step, simulator-based approach, yielding explicit conditions that guarantee LWE-OD is at least as computationally hard as LWE. While this theorem provides a valuable reduction, it also highlights a crucial distinction among reductions: those that allow explicit calculation of target distributions versus weaker ones with conditional results. To further demonstrate the utility of our framework, we offer new proofs for existing results, specifically the reduction from LWE to LWR and from LPN to Learning Parity with Noise with Output Dependencies (LPN-OD). This new reduction opens the door for a potential reduction from LWE to LWPR.'
---
