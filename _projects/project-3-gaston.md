---
title: "Gaston: Decision Procedure for WS1S Logic"
excerpt: "Gaston is an implementation of backward decision procedure logic for WS1S logic."
collection: projects
github: "https://github.com/tfiedor/gaston"
tags:
  - ws1s
  - decision procedure
  - nondeterministic finite automata
---
|           |                                                                                       |
|-----------|---------------------------------------------------------------------------------------|
| Github    | [tfiedor/gaston](https://github.com/tfiedor/gaston)                                   |
| Website   | [fit.vutbr.cz/gaston](https://www.fit.vutbr.cz/research/groups/verifit/tools/gaston/) |

[<i class="fab fa-fw fa-github zoom" aria-hidden="true"></i> More on github!](https://github.com/tfiedor/gaston)

## My contributions

1. I was the main developer of the Gaston (while being mentored by Ondra Lengál).
2. I created the original prototype called `dWiNA`, that was extended to become `gaston`.
3. I was the main designer for the experimental evaluation: how the benchmarks were run, how the benchmarks were
   evaluated, and how the results were presented (currently unpublished). I also created a replication package for
   evaluating the strenghts of our library.

`gaston` is no longer maintained.

##

To install `gaston`, run the following:

```shell
git clone https://github.com/tfiedor/Gaston.git
make release
```

## Overview

Gaston is an implementation of backward decision procedure for WS1S logic (weak second-order theory
of k successors). The tool is using libmona a highly optimised deterministic finite tree automata
library that supports semi-symbolic encoding using multi-terminal binary decision diagrams (MTBDDs)
for storing transition table of the automaton. Procedure generates state space on-the-fly and
prunes the states using the antichain-based approach. The tool works on the symbolical
representation of the formula as Symbolic Automata and tries to prove on-the-fly that the initial
states intersect the final states to (dis)prove validity.

## Licence

The code of `gaston` is licensed under MIT licence.

## Other contributors

* Tomas Fiedor <ifiedortom@fit.vutbr.cz> (corresponding author of Gaston)
* Lukas Holik <holik@fit.vutbr.cz>
* Petr Janku <ijanku@fit.vutbr.cz> (optimizations of MONA wrapper)
* Ondrej Lengal <ilengal@fit.vutbr.cz> (corresponding author of VATA)
* Tomas Vojnar <vojnar@fit.vutbr.cz>
