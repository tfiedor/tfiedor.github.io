---
title: "Martina Grzybowská: Graphical User Interface for Performance Control System"
collection: students
type: "Bachelor's Thesis"
excerpt: 'The goal of this thesis was to create a graphical user interface for my Perun project. The GUI was realized based on
modern approaches to website development using `vue.js` framework.
The GUI is, however, currently outdated and not merged in our upstream.'
permalink: /students/2018-01-bp-martina
paperurl: 'http://tfiedor.github.io/files/thesis/grzybowska-bp.pdf'
tags:
  - perun
  - gui
  - performance testing
gallery:
  - url: students/martina-bp-1.JPG
    image_path: students/martina-bp-1.JPG
    alt: "an example of commit history visualized in the GUI"
    title: "An example of commit history visualized in the GUI."
  - url: students/martina-bp-2.JPG
    image_path: students/martina-bp-2.JPG
    alt: "an example of overview dashboard visualized in the GUI"
    title: "An example of overview dashboard visualized in the GUI."
  - url: students/martina-bp-3.JPG
    image_path: students/martina-bp-3.JPG
    alt: "an example of overview of all repositories on system visualized in the GUI"
    title: "An example of overview of all repositories on system visualized in the GUI."
---

|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Thesis Detail        | [Institution site](https://www.vut.cz/studenti/zav-prace/detail/114556) |
| Thesis Download      | [Thesis Download](https://www.vut.cz/www_base/zav_prace_soubor_verejne.php?file_id=180733) |

The goal of this thesis was to create a graphical user interface for my Perun project. The GUI was realized based on
modern approaches to website development using `vue.js` framework.
The GUI is, however, currently outdated and not merged in our upstream.

## Abstract

One of the most frequent ways to test system performance is the program profiling technique, which carries out a
collection of resource consumption data and its subsequent evaluation leading to the detection of performance changes,
whose existence may have a negative impact on the system in development. For the realization of the profiling process
and more complex application performance management, there are several established solutions. Perun belongs among the
newer performance managers, it provides automatization of creating as well as managing of the performance profiles.
However, the current version only offers a console user interface, therefore it is not suitable for deployment to e.g.
cloud. The main objective of this thesis is to specify, design and implement a graphical user interface for Perun. The
resulting interface targets the core functionality such as profiling data collection based on the pre-defined
configuration, its subsequent postprocessing or effective visualization, as well as the ability to clearly give
information about the status of performance degradation among individual project versions. The solution is demonstrated
on three non-trivial version control systems annotated by performance profiles.

{% include gallery %}
