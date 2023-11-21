---
title: "Šimon Stupinský: New Models for Automatic Detection of Performance Degradation"
collection: students
type: "Bachelors's Thesis"
permalink: /students/2019-03-bp-simon
---

Disclaimer: While this thesis was officially supervised by Adam Rogalewicz (due some internal restrictions), I
was the main supervisor of this whole thesis. The goal of this thesis was to extend the capabilities of Perun with new
models (besides so-far supported regression analysis) as well as new approaches to detect performance degradations in
software.
In particular, we come up with non-parametric models (models not dependent on other variables) such as regressograms,
moving averages or kernel regressions; as well as methods for detecting performance issues based on integral computation
or local statistics.

## Abstract

Performance testing is a critical factor in the optimisation of programs during its development,
but it is still not so well developed in comparison to functional testing. A framework Perun
provides full automation of performance management, thereby contributing to the development of this
area. We have introduced three non-parametric approaches to performance data modelling:
regressogram, moving average and kernel regression, which were integrated within this framework. We
try to achieve appropriate approximations of performance data using these techniques, without the
assumption of dependence between two variables, which represents the main advantage in comparison
to parametric techniques. Further, we have proposed and implemented two methods for automatic
detection of performance changes, which works with all kinds of models within Perun. We have
demonstrated our solutions on the real project (Vim), and on the set of the experimental cases, in
which we compared proposed solutions with existing. We have achieved decreased time processing
about two-thirds and an almost triple improvement in the fitness of data modelling with new
modelling approaches. The proposed detection methods detected performance degradation of three
specific functions in comparison of two different versions of Vim, where was present a known
performance issue.
