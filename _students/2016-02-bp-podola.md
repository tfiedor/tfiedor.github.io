---
title: "Radim Podola: Library for Profiling and Visualization of Memory Consumption of C/C++ Programs"
collection: students
type: "Bachelor's Thesis"
excerpt: 'The goal of this thesis was to create a memory profiler of C/C++. The results were interpretered using several kinds of
visualizations: (1) heat maps (both in GUI and in CLI using `ncurses` library), and (2) flamegraphs.'
permalink: /students/2016-02-bp-podola
paperurl: 'http://tfiedor.github.io/files/thesis/podola-bp.pdf'
tags:
  - perun
  - performance testing
  - memory
gallery:
  - url: students/podola-bp-1.JPG
    image_path: students/podola-bp-1.JPG
    alt: "a visualization of heap map: showing which allocations have allocated memory on which
    addresses"
    title: "A visualization of heap map: showing which allocations have allocated memory on which
    addresses"
  - url: students/podola-bp-2.JPG
    image_path: students/podola-bp-2.JPG
    alt: "a visualization of heat map: showing which addresses were mostly allocated on."
    title: "A visualization of heat map: showing which addresses were mostly allocated on."
---

|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Thesis Detail        | [Institution site](https://www.vut.cz/studenti/zav-prace/detail/106155) |
| Thesis Download      | [Thesis Download](https://www.vut.cz/www_base/zav_prace_soubor_verejne.php?file_id=158576) |

The goal of this thesis was to create a memory profiler of C/C++. The results were interpretered using several kinds of
visualizations: (1) heat maps (both in GUI and in CLI using `ncurses` library), and (2) flamegraphs.

## Abstract

Performance is an important and, for some classes of programs, even critical aspect of user experience. The current
approaches to performance profiling are, however, far from being satisfactory. The aim of this bachelor's thesis is to
extend the current state-of-the-art of profiling and visualization solutions, with novel techniques which can be used
for a more efficient search of performance bugs in C/C++ programs and their subsequent interpretation to the end user.
Thesis briefly introduces existing tools dealing with similar problems and then proposes a novel solution to collection
of profiling data and their illustrative interpretation. The resulting implementation is, moreover, integrated in the
Perun --- Performance Control System --- platform for profile versioning. The functionality of the implementation is
demonstrated on a series of non-trivial programs.

{% include gallery %}
