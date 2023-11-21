---
title: "Nested Antichains for WS1S"
collection: publications
permalink: /publication/2019-01-nested-antichains
excerpt: "This is an extended journal version of our TACAS'15 paper"
date: 2019-10-01
venue: 'Acta Informatica'
paperurl: 'https://tfiedor.github.io/files/pubs/2019-01-nested-antichains.pdf'
doi: "https://doi.org/10.1007/s00236-018-0331-z"
keywords: "ws1s logic, antichains, nondeterministic finite automata, decision procedure"
gallery:
  - url: pubs/2019-01-nested-antichains-gallery-1.png
    image_path: pubs/2019-01-nested-antichains-gallery-1.png
    alt: "results for strand benchmark"
    title: "Comparison of our approach (dWiNA) with state-of-the-art tool MONA on strand benchmark"
  - url: pubs/2019-01-nested-antichains-gallery-2.png
    image_path: pubs/2019-01-nested-antichains-gallery-2.png
    alt: "results for HornSub benchmark"
    title: "Comparison of our approach (dWiNA) with state-of-the-art tool MONA on HornSub benchmark"
  - url: pubs/2019-01-nested-antichains-gallery-3.png
    image_path: pubs/2019-01-nested-antichains-gallery-3.png
    alt: "results for parametric benchmark"
    title: "Comparison of our approach (dWiNA) with state-of-the-art tool MONA on parametric formulae. The notion of k depends on the family. The higher the k, the more complex the formula is."
---
|                  |                                                                                              |
|------------------|----------------------------------------------------------------------------------------------|
| Institution Link | [Institution information (fit.vutbr.cz)](https://www.fit.vut.cz/research/publication/11889/) |
| Journal          | [ActaInformatica](https://www.springer.com/journal/236)                                      |
| Impact Factor    | 0.6 (2022)                                                                                   |

This is an extended version of our paper [Nested antichains for WS1S](tfiedor.github.io/pubs/2015-01-nested-antichains).

[<i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i> Download paper here](https://tfiedor.github.io/files/pubs/2019-01-nested-antichains.pdf)

## My contributions

1. I helped with extension of the journal to include additional theory and explanations that did not fit to previous
   paper.
2. I created a running example to better illustrate our techniques and notions.

## Abstract

We propose a novel approach for coping with alternating quantification as the main source of nonelementary complexity of
deciding WS1S formulae. Our approach is applicable within the state-of-the-art automata-based WS1S decision procedure
implemented e.g. in Mona. The way in which the standard decision procedure processes quantifiers involves
determinization, with its worst case exponential complexity, for every quantifier alternation in the prefix of a
formula. Our algorithm avoids building the deterministic automata---instead, it constructs only those of their states
needed for (dis)proving validity of the formula. It uses a symbolic representation of the states, which have a deeply
nested structure stemming from the repeated implicit subset construction, and prunes the search space by a nested
subsumption relation, a generalization of the one used by the so-called antichain algorithms for handling
nondeterministic automata. We have obtained encouraging experimental results, in some cases outperforming Mona, and some
of the other recently proposed approaches, by several orders of magnitude.

{% include gallery %}

###  Cite us

> FIEDOR Tomáš, HOLÍK Lukáš, LENGÁL Ondřej and VOJNAR Tomáš. Nested Antichains for WS1S. Acta Informatica, vol. 56, no. 3, 2019, pp. 205-228. ISSN 0001-5903.
