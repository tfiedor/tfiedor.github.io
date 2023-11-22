---
title: "Lazy Automata Techniques for WS1S"
collection: publications
permalink: /publication/2017-01-lazy-techniques
excerpt: 'This paper is our follow-up work on deciding WS1S logic using non-deterministic finite automata'
date: 2017-10-01
venue: 'TACAS'
paperurl: 'http://tfiedor.github.io/files/pubs/2017-01-lazy-techniques.pdf'
doi: "https://doi.org/10.1007/978-3-662-54577-5_24"
citation: "FIEDOR Tomáš, HOLÍK Lukáš, JANKŮ Petr, LENGÁL Ondřej and VOJNAR Tomáš. Lazy Automata Techniques for WS1S. In: Proceedings of TACAS'17. Lecture Notes in Computer Science, vol. 10205. Heidelberg: Springer Verlag, 2017, pp. 407-425. ISBN 978-3-662-54576-8. ISSN 0302-9743."
tags: 
   - nondeterministic finite automata 
   - ws1s logic 
   - lazy techniques 
   - anti-chains 
   - decision procedures
gallery:
  - url: pubs/2017-01-lazy-gallery-1.png
    image_path: pubs/2017-01-lazy-gallery-1.png
    alt: "an example of lazy approach to deciding ws1s formulae"
    title: "An example of our approach, that determines whether the automaton is empty (resp. formula is invalid) on-the-fly exploiting lazy techniques."
  - url: pubs/2017-01-lazy-gallery-2.png
    image_path: pubs/2017-01-lazy-gallery-2.png
    alt: "results of our tool Gaston on UABE benchmark"
    title: "Comparison of our tool Gaston with state-of-the-art tool MONA on UABE benchmark."
  - url: pubs/2017-01-lazy-gallery-3.png
    image_path: pubs/2017-01-lazy-gallery-3.png
    alt: "results of our tool Gaston on Strand benchmark"
    title: "Comparison of our tool Gaston with state-of-the-art tool MONA on Strand benchmark."
  - url: pubs/2017-01-lazy-gallery-4.png
    image_path: pubs/2017-01-lazy-gallery-4.png
    alt: "results of our tool Gaston on parametric benchmarks"
    title: "Comparison of our tool Gaston with state-of-the-art tools on parametric benchmarks."
---

|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Institution Link     | [Institution site (fit.vutbr.cz)](https://www.fit.vut.cz/research/publication/11323/)                                               |
| Additional Resources | [Paper website](https://www.fit.vutbr.cz/research/groups/verifit/tools/gaston)                                                      |
| Conference           | [23rd International Conference on Tools and Algorithms for the Construction and Analysis of Systems ](https://etaps.org/2017/tacas) |
| Conference Ranking   | A                                                                                                                                   |

[<i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i> Download paper here](http://tfiedor.github.io/files/pubs/2017-01-lazy-techniques.pdf)

## My contributions

1. While I was not the author of the main idea, I helped shaped the final decision procedure and came up with several
   significant optimisations of the process.
2. I was the main developer of the decision procedure; I implemented numbers optimisations of the process (both minor
   and major).
3. I run the experiments and interpreted the results.

## Abstract

We present a new decision procedure for the logic WS1S. It originates from the classical approach,
which first builds an automaton accepting all models of a formula and then tests whether its
language is empty. The main novelty is to test the emptiness on the fly, while constructing the
automaton, and prune the constructed state space from parts irrelevant for the test. The pruning is
done by a~generalization of two techniques used in antichain-based language inclusion and
universality checking of finite automata: subsumption and early termination. The~richer structure
of the WS1S decision problem allows us, however, to elaborate on these techniques in novel ways.
Our experiments show that the proposed approach can indeed significantly outperform the classical
decision procedure (implemented in the \mona~tool) as well as its recently proposed alternative
based on using nondeterministic automata.

{% include gallery %}

###  Cite us

> FIEDOR Tomáš, HOLÍK Lukáš, JANKŮ Petr, LENGÁL Ondřej and VOJNAR Tomáš. Lazy Automata Techniques for WS1S. In: Proceedings of TACAS'17. Lecture Notes in Computer Science, vol. 10205. Heidelberg: Springer Verlag, 2017, pp. 407-425. ISBN 978-3-662-54576-8. ISSN 0302-9743.
