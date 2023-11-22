---
title: "Nested Antichains for WS1S"
collection: publications
permalink: /publication/2015-01-nested-antichains
excerpt: 'This paper is our initial work on deciding WS1S logic using non-deterministic finite automata'
date: 2015-10-01
venue: 'TACAS'
paperurl: 'http://tfiedor.github.io/files/pubs/2015-01-nested-antichains.pdf'
doi: "http://dx.doi.org/10.1007/978-3-662-46681-0_59"
citation: "FIEDOR Tomáš, HOLÍK Lukáš, LENGÁL Ondřej and VOJNAR Tomáš. Nested Antichains for WS1S. In: Proceedings of TACAS'15. Lecture Notes in Computer Science, vol. 9035. Heidelberg: Springer Verlag, 2015, pp. 658-674. ISBN 978-3-662-46680-3."
tags: 
   - nondeterministic finite automata
   - ws1s logic
   - anti-chains 
   - decision procedures
gallery:
  - url: pubs/2015-01-anti-gallery-1.png
    image_path: pubs/2015-01-anti-gallery-1.png
    alt: "an example of lazy approach to deciding ws1s formulae"
    title: "An example of our approach, that determines whether the automaton is empty (resp. formula is invalid) on-the-fly exploiting lazy techniques."
  - url: pubs/2015-01-anti-gallery-2.png
    image_path: pubs/2015-01-anti-gallery-2.png
    alt: "results of our tool Gaston on UABE benchmark"
    title: "Comparison of our tool Gaston with state-of-the-art tool MONA on UABE benchmark."
---

|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Institution Link     | [Institution site (fit.vutbr.cz)](https://www.fit.vut.cz/research/publication/10790/)                                               |
| Additional Resources | [Paper website](https://www.fit.vutbr.cz/research/groups/verifit/tools/dWiNA)                                                       |
| Conference           | [21rd International Conference on Tools and Algorithms for the Construction and Analysis of Systems ](https://etaps.org/2015/tacas) |
| Conference Ranking   | A                                                                                                                                   |


[<i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i> Download paper here](http://tfiedor.github.io/files/pubs/2015-01-nested-antichains.pdf)

## My contributions

1. While I was not the author of the main idea, I helped shaped the final decision procedure and came up with several
   significant optimisations of the process.
2. I was the main developer of the decision procedure.
3. I run the experiments and interpreted the results.

## Abstract

We propose a novel approach for coping with alternating quantification as the main source of
nonelementary complexity of deciding WS1S formulae. Our approach is applicable within the
state-of-the-art automata-based WS1S decision procedure implemented, e.g., in MONA. The way in
which the standard decision procedure processes quantifiers involves determinization, with its
worst case exponential complexity, for every quantifier alternation in the prefix of a formula. Our
algorithm avoids building the deterministic automata-instead, it constructs only those of their
states needed for (dis)proving validity of the formula. It uses a symbolic representation of the
states, which have a deeply nested structure stemming from the repeated implicit subset
construction, and prunes the search space by a nested subsumption relation, a generalisation of the
one used by the so-called antichain algorithms for handling non-deterministic automata. We have
obtained encouraging experimental results, in some cases outperforming MONA by several orders of
magnitude.

{% include gallery %}

###  Cite us

> FIEDOR Tomáš, HOLÍK Lukáš, LENGÁL Ondřej and VOJNAR Tomáš. Nested Antichains for WS1S. In: Proceedings of TACAS\'15. Lecture Notes in Computer Science, vol. 9035. Heidelberg: Springer Verlag, 2015, pp. 658-674. ISBN 978-3-662-46680-3.
