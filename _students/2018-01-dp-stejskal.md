---
title: "Jakub Stejskal: Performance Testing and Analysis of Qpid Dispatch Router"
collection: students
type: "Master's Thesis"
excerpt: 'Disclaimer: This thesis was supervised together with RedHat company; I served mainly as a formal supervisor;
technical consultants were Zdeněk Kraus and Otavio Rodolfo Piske. This thesis goal was to extend the capabilities of
performance testing conducted in Red Hat company.'
permalink: /students/2016-01-dp-stejskal
paperurl: 'http://tfiedor.github.io/files/thesis/stejskal-dp.pdf'
tags:
  - external
  - redhat
  - performance testing
  - network analysis
gallery:
  - url: students/stejskal-dp-1.JPG
    image_path: students/stejskal-dp-1.JPG
    alt: "latency chart showing the difference between the router and broker latency at 80% maximal
    rate"
    title: "Latency chart showing the difference between the router and broker latency at 80% maximal rate."
  - url: students/stejskal-dp-2.JPG
    image_path: students/stejskal-dp-2.JPG
    alt: "examples of experimental topologies created for basic performance testing and experiments
    with Maestro"
    title: "Examples of experimental topologies created for basic performance testing and experiments
    with Maestro."
---

|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Thesis Detail        | [Institution site](https://www.vut.cz/studenti/zav-prace/detail/114875) |
| Thesis Download      | [Thesis Download](https://www.vut.cz/www_base/zav_prace_soubor_verejne.php?file_id=181688) |

Disclaimer: This thesis was supervised together with RedHat company; I served mainly as a formal supervisor;
technical consultants were Zdeněk Kraus and Otavio Rodolfo Piske. This thesis goal was to extend the capabilities of
performance testing conducted in Red Hat company.

## Abstract

Application performance testing has recently become more important during the application development of all kinds. This
paper maps the fundamentals of performance testing that are commonly used and it analyzes performance testing of
components used in Messaging systems, especially Apache ActiveMQ Artemis and Qpid-Dispatch. However, currently used
methods for performance testing of these components are primarily focused only on Apache ActiveMQ Artemis by system
Messaging Performance Tool called Maestro. This paper proposes improvements of Messaging Performance Tool to allow
proper performance testing of Qpid-Dispatch and its capabilities in automatic testing. The solution is demonstrated on
series of experiments with different topologies. The final report evaluates the proposed application, the performance of
Qpid-Dispatch component and develops ideas for future works.

{% include gallery %}
