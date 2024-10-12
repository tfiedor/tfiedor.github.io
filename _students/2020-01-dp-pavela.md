---
title: "Jiří Pavela: Efficient Techniques for Program Performance Analysis"
collection: students
type: "Masters's Thesis"
excerpt: "The goal of this work was to optimize the profiling time and space based
on several aspects of projects or profiling process: based on structure of the profiled program, based on complexity of
the analysed functions, or recency of the changes. This is without doubt, my most favourite work I have supervised."
permalink: /students/2020-01-dp-pavela
paperurl: 'http://tfiedor.github.io/files/thesis/jirka-dp.pdf'
tags:
  - perun
  - profiling
  - optimization
gallery:
  - url: students/jirka-dp-1.JPG
    image_path: students/jirka-dp-1.JPG
    alt: "a comparison of ebpf and system tap engines for profiling program using different
    strategies"
    title: "A comparison of ebpf and system tap engines for profiling program using different
    strategies."
---
|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Thesis Detail        | [Institution site](https://www.vut.cz/studenti/zav-prace/detail/129252) |
| Thesis Download      | [Thesis Download](https://www.vut.cz/www_base/zav_prace_soubor_verejne.php?file_id=215984) |

Disclaimer: While this thesis was officially supervised by Adam Rogalewicz (due some internal restrictions), I
was the main supervisor of this whole thesis. The goal of this work was to optimize the profiling time and space based
on several aspects of projects or profiling process: based on structure of the profiled program, based on complexity of
the analysed functions, or recency of the changes. This is without doubt, my most favourite work I have supervised.

## Abstract

In this work, we propose optimization techniques focused on the data collection process of program performance analysis
and profiling within the Perun framework. We enhance Perun (and especially its Tracer module) by extending their
architecture and implementing novel optimization techniques that allow Perun to scale well even for large projects and
test scenarios. In particular, we focus on improving the data collection precision, scaling down the amount of injected
instrumentation, limiting the time overhead of the collection and profiling processes, reducing the volume of raw
performance data and the size of the resulting profile. To achieve such optimization, we utilized statistical methods,
several static and dynamic analysis approaches (as well as their combination) and exploited the advanced features and
capabilities of SystemTap and eBPF frameworks. Based on the evaluation performed on two selected projects and numerous
experiment cases, we were able to conclude that we successfully achieved significant levels of optimization for nearly
all of the identified metrics and criteria.

{% include gallery %}
