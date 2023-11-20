---
title: "Lazy Automata Techniques for WS1S"
collection: publications
permalink: /publication/2017-01-lazy-techniques
excerpt: 'This paper is our follow-up work on deciding WS1S logic using non-deterministic finite
automata'
date: 2017-10-01
venue: 'TACAS'
paperurl: 'http://tfiedor.github.io/files/2017-01-lazy-techniques.pdf'
citation: "FIEDOR Tomáš, HOLÍK Lukáš, JANKŮ Petr, LENGÁL Ondřej and VOJNAR Tomáš. Lazy Automata Techniques for WS1S. In: Proceedings of TACAS'17. Lecture Notes in Computer Science, vol. 10205. Heidelberg: Springer Verlag, 2017, pp. 407-425. ISBN 978-3-662-54576-8. ISSN 0302-9743."
---

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

[Download paper here](http://tfiedor.github.io/files/2017-01-lazy-techniques.pdf)
Recommended citation: FIEDOR Tomáš, HOLÍK Lukáš, JANKŮ Petr, LENGÁL Ondřej and VOJNAR Tomáš. Lazy Automata Techniques for WS1S. In: Proceedings of TACAS'17. Lecture Notes in Computer Science, vol. 10205. Heidelberg: Springer Verlag, 2017, pp. 407-425. ISBN 978-3-662-54576-8. ISSN 0302-9743.
