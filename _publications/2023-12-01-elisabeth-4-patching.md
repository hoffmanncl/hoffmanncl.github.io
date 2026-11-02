---
title: 'The Patching Landscape of Elisabeth-4 and the Mixed Filter Permutator Paradigm'
collection: publications
date: 2023-12-01
venue: 'Indocrypt 2023'
authors:
  - 'Clément Hoffmann'
  - 'Pierrick Méaux'
  - 'François-Xavier Standaert'
eprint: 'https://eprint.iacr.org/2023/1895'
doi: 'https://doi.org/10.1007/978-3-031-56232-7_7'
abstract: 'Filter permutators are a family of stream cipher designs that are aimed for hybrid homomorphic encryption. While originally operating on bits, they have been generalized to groups at Asiacrypt 2022, and instantiated for evaluation with the TFHE scheme which favors a filter based on (negacyclic) Look Up Tables (LUTs). A recent work of Gilbert et al., to appear at Asiacrypt 2023, exhibited (algebraic) weaknesses in the Elisabeth-4 instance, exploiting the combination of the 4-bit negacyclic LUTs it uses as filter. In this article, we explore the landscape of patches that can be used to restore the security of such designs while maintaining their good properties for hybrid homomorphic encryption. Starting with minimum changes, we observe that just updating the filter function (still with small negacyclic LUTs) is conceptually feasible, and propose the resulting Elisabeth-b4 design with three levels of NLUTs. We then show that a group permutator combining two different functions in the filter can simplify the analysis and improve performances. We specify the Gabriel instance to illustrate this claim. We finally propose to modify the group filter permutator paradigm into a mixed filter permutator, which considers the permutation of the key with elements in a group and a filter outputting elements in a different group. We specify the Margrethe instance as a first example of mixed filter permutator, with key elements in 𝔽₂ and output in ℤ₁₆, that we believe well-suited for recent fully homomorphic encryption schemes that can efficiently evaluate larger (not negacyclic) LUTs.'
---
