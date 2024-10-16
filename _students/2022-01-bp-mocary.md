---
title: "Peter Močáry: Performance Analysis of Programs Based on PIN Framework"
collection: students
type: "Bachelor's Thesis"
permalink: /students/2022-01-bp-mocary
excerpt: "Disclaimer: This thesis was mainly supervised by Ing. Jiří Pavela; I have served as additional technical
consultant. The goal of this thesis was to extend our `trace` profiler with support for PIN framework.
This would allow us to overcome some of the limitations of our current underlying instrumentation frameworks (eBPF and
SystemTap)."
paperurl: 'http://tfiedor.github.io/files/thesis/peter-bp.pdf'
tags:
  - PIN
  - profiling
  - basic block analysis
gallery:
  - url: students/peter-bp-1.JPG
    image_path: students/peter-bp-1.JPG
    alt: "an example comparison of two function on basic block granularity"
    title: "An example comparison of two function on basic block granularity."
---
|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Thesis Detail        | [Institution site](https://www.vut.cz/studenti/zav-prace/detail/145076) |
| Thesis Download      | [Thesis Download](https://www.vut.cz/www_base/zav_prace_soubor_verejne.php?file_id=244756) |

Disclaimer: This thesis was mainly supervised by Ing. Jiří Pavela; I have served as additional technical
consultant. The goal of this thesis was to extend our `trace` profiler with support for PIN framework.
This would allow us to overcome some of the limitations of our current underlying instrumentation frameworks (eBPF and
SystemTap).

## Abstract

The goal of this thesis is to extend the Performance Version System - Perun by implementing a new Tracer engine
leveraging PIN instrumentation framework. This extension implements basic Tracer functionality and, in addition to that,
a recording of function arguments' values as well as basic block run-times. The additional data, along with the
visualizations introduced in this thesis, provide the necessary context that simplifies the detection of performance
degradation. Besides the PIN framework, the new Tracer engine implements an analysis of debug information in DWARF
format (using the python pyelftools library) to gather details about function arguments before the data collection
process. The resulting engine was tested on multiple implementations of sorting algorithms and successfully detected the
most time consuming functions along with the information about the effect of its parameter value on the functions
complexity. Testing the PIN engine on a larger-scale project revealed that, in comparison to other Tracer engine
implementations, the engine performs better or comparably, and produces the correct output.

{% include gallery %}
