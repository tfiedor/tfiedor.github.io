---
title: "Vojtěch Hájek: Performance Analysis of C# Programs"
collection: students
type: "Bachelor's Thesis"
permalink: /students/2023-01-bp-hajek
excerpt: "Disclaimer: This thesis was mainly supervised by Ing. Jiří Pavela; I have served as additional technical
consultant. The goal of this thesis was to extend our profilers with profiler for programs written in C#, potentially
extending our support for Windows (sub)systems. The results were interpreted using tree-like views similar to outputs"
paperurl: 'http://tfiedor.github.io/files/thesis/vojta-bp.pdf'
tags:
  - perun
  - C#
  - profiling
  - tree map
  - scatter plot
gallery:
  - url: students/vojta-bp-1.JPG
    image_path: students/vojta-bp-1.JPG
    alt: "a visualization of allocated objects in time as scatter plot"
    title: "A visualization of allocated objects in time as scatter plot."


of `kcachegrind`.
---

|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Thesis Detail        | [Institution site](https://www.vut.cz/studenti/zav-prace/detail/148641) |
| Thesis Download      | [Thesis Download](https://www.vut.cz/www_base/zav_prace_soubor_verejne.php?file_id=252289) |

Disclaimer: This thesis was mainly supervised by Ing. Jiří Pavela; I have served as additional technical
consultant. The goal of this thesis was to extend our profilers with profiler for programs written in C#, potentially
extending our support for Windows (sub)systems. The results were interpreted using tree-like views similar to outputs
of `kcachegrind`.

## Abstract

The goal of this thesis is to extend the Performance Version System – Perun by implementing a module for profiling
programs written in C# language. This extension implements a tracing profiler with the use of .NET runtime profiling
aplication interface. Profiler can collect metrics about trace functions and memory consumption. Measured profiles can
then be interpreted into graphs like a scatter plot or a treemap.

{% include gallery %}
