---
title: "Ondřej Pavela: Static Analysis Using Facebook Infer Focused on Performance Analysis"
collection: students
type: "Bachelors's Thesis"
permalink: /students/2019-01-bp-ondra
---

Disclaimer: This thesis was supervised by Tomáš Vojnar, I was the technical consultant.
The goal of this thesis was build upon our work on automatic complexity analysis; this was initial work that only had to
reproduce the results of Loopus tools invented by our colleagues in TU Vienna (Moritz Sinn and Florian Zuleger)
in the Facebook Infer framework.

## Abstract

Static analysis has nowadays become one of the most popular ways of catching bugs early in the modern software. However,
reasonably precise static analysis tools still often struggle to scale well on large and quickly changing codebases.
Efficient static analysers, such as Coverity or Code Sonar, are usually proprietary and difficult to openly evaluate or
extend. On the contrary, Facebook Infer offers an open source static analysis framework with the emphasis on
compositional, incremental and consequently highly scalable inter-procedural analysis. This thesis presents Looper --- a
new performance oriented resource bounds analyser which extends the capabilities of Facebook Infer. We have based our
implementation on an existing resource bounds analyser Loopus and evaluated it on two different test suites, showing
encouraging results in comparison with the existing Cost analyser developed by the Infer team.
