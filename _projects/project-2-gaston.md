---
title: "Gaston: Decision Procedure for WS1S Logic"
excerpt: "Gaston is an implementation of backward decision procedure logic for WS1S logic."
collection: projects
---

Gaston is an implementation of backward decision procedure for WS1S logic (weak second-order theory
of k successors). The tool is using libmona a highly optimised deterministic finite tree automata
library that supports semi-symbolic encoding using multi-terminal binary decision diagrams (MTBDDs)
for storing transition table of the automaton. Procedure generates state space on-the-fly and
prunes the states using the antichain-based approach. The tool works on the symbolical
representation of the formula as Symbolic Automata and tries to prove on-the-fly that the initial
states intersect the final states to (dis)prove validity.
