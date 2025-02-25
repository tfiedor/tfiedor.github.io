---
title: "Matúš Liščinský: Performance Analysis Based on Noise Injection"
collection: students
type: "Masters's Thesis"
excerpt: "The goal of this thesis was to extend the capabilities of Perun with injecting noise into program to either simulate
potential code optimisations or to make performance issues manifest during profiling."
permalink: /students/2021-01-dp-matus
paperurl: 'http://tfiedor.github.io/files/thesis/matus-dp.pdf'
tags:
  - noise injection
  - performance blowing
  - performance analysis
---

|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Thesis Detail        | [Institution site](https://www.vut.cz/studenti/zav-prace/detail/136829) |
| Thesis Download      | [Thesis Download](https://www.vut.cz/www_base/zav_prace_soubor_verejne.php?file_id=231285) |


The goal of this thesis was to extend the capabilities of Perun with injecting noise into program to either simulate
potential code optimisations or to make performance issues manifest during profiling.

## Abstract

In this work, we proposed a Perun-Blower framework which utilises the perfblowing technique: injecting of noise into the
functions of the tested program, followed by collecting of runtime data of these functions from the program run and
evaluating the impact of the noise on the program performance. We build on the dynamic binary instrumentation of the Pin
framework to inject the noise into program. We then focus on finding functions with high impact on performance as well
as estimate the thread run's potential acceleration when optimising the particular functions. Moreover, we have extended
the existing Trace collector used in the Perun framework to collect the runtime of functions with a new so-called engine
based on the Pin framework. We tested the functionality of our implementation on two non-trivial projects, where we were
able to find functions (1) with considerable impact on performance, (2) with the most significant optimisation benefit,
and (3) whose degradation forces the non-termination of the program after several hours of running.

{% include gallery %}
