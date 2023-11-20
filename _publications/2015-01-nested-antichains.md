---
title: "Nested Antichains for WS1S"
collection: publications
permalink: /publication/2015-01-nested-antichains
excerpt: 'This paper is our initial work on deciding WS1S logic using non-deterministic finite
automata'
date: 2015-10-01
venue: 'TACAS'
paperurl: 'http://tfiedor.github.io/files/2015-01-nested-antichains.pdf'
citation: "FIEDOR Tomáš, HOLÍK Lukáš, LENGÁL Ondřej and VOJNAR Tomáš. Nested Antichains for WS1S. In: Proceedings of TACAS'15. Lecture Notes in Computer Science, vol. 9035. Heidelberg: Springer Verlag, 2015, pp. 658-674. ISBN 978-3-662-46680-3."
---

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

[Download paper here](http://tfiedor.github.io/files/2015-01-nested-antichains.pdf)
Recommended citation: FIEDOR Tomáš, HOLÍK Lukáš, LENGÁL Ondřej and VOJNAR Tomáš. Nested Antichains for WS1S. In: Proceedings of TACAS\'15. Lecture Notes in Computer Science, vol. 9035. Heidelberg: Springer Verlag, 2015, pp. 658-674. ISBN 978-3-662-46680-3.
