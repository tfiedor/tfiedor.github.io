---
title: "Nested Antichains for WS1S"
collection: publications
permalink: /publication/2019-01-nested-antichains
excerpt: "This is an extended journal version of our TACAS'15 paper"
date: 2019-10-01
venue: 'TACAS'
paperurl: 'http://tfiedor.github.io/files/2018-01-nested-antichains.pdf'
citation: "FIEDOR Tomáš, HOLÍK Lukáš, LENGÁL Ondřej and VOJNAR Tomáš. Nested Antichains for WS1S. Acta Informatica, vol. 56, no. 3, 2019, pp. 205-228. ISSN 0001-5903."
---

We propose a novel approach for coping with alternating quantification as the main source of nonelementary complexity of deciding WS1S formulae. Our approach is applicable within the state-of-the-art automata-based WS1S decision procedure implemented e.g. in Mona. The way in which the standard decision procedure processes quantifiers involves determinization, with its worst case exponential complexity, for every quantifier alternation in the prefix of a formula. Our algorithm avoids building the deterministic automata---instead, it constructs only those of their states needed for (dis)proving validity of the formula. It uses a symbolic representation of the states, which have a deeply nested structure stemming from the repeated implicit subset construction, and prunes the search space by a nested subsumption relation, a generalization of the one used by the so-called antichain algorithms for handling nondeterministic automata. We have obtained encouraging experimental results, in some cases outperforming Mona, and some of the other recently proposed approaches, by several orders of magnitude.

[Download paper here](http://tfiedor.github.io/files/2019-01-nested-antichains.pdf)
Recommended citation: FIEDOR Tomáš, HOLÍK Lukáš, LENGÁL Ondřej and VOJNAR Tomáš. Nested Antichains for WS1S. Acta Informatica, vol. 56, no. 3, 2019, pp. 205-228. ISSN 0001-5903.
