---
title: "Milan Lysoňek: Existing Attacks on SSL/TLS Protocol"
collection: students
type: "Bachelor's Thesis"
excerpt: 'Disclaimer: This thesis was supervised together with RedHat company; I served mainly as a formal
superviser; technical consultant were Stanislav Židek and Hubert Kario. The goal of the thesis was
to extend the capabilities of testing attacks based on fuzztesting solved within the RedHat
company.'
paperurl: 'http://tfiedor.github.io/files/thesis/lysonek-bp.pdf'
permalink: /students/2016-03-bp-lysonek
tags:
  - fuzzing
  - security
  - external
  - redhat
gallery:
  - url: students/lysonek-bp-1.JPG
    image_path: students/lysonek-bp-1.JPG
    alt: "results of fuzztesting applied to different versions of SSL versions"
    title: "Results of fuzztesting applied to different versions of SSL versions."
---

|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Thesis Detail        | [Institution site](https://www.vut.cz/studenti/zav-prace/detail/106438) |
| Thesis Download      | [Thesis Download](https://www.vut.cz/www_base/zav_prace_soubor_verejne.php?file_id=159423) |

Disclaimer: This thesis was supervised together with RedHat company; I served mainly as a formal
superviser; technical consultant were Stanislav Židek and Hubert Kario. The goal of the thesis was
to extend the capabilities of testing attacks based on fuzztesting solved within the RedHat
company.

## Abstract

SSL/TLS is a modern cryptographic protocol, which secures the communication between client and
server. However, there are attacks on this protocol which can compromise communication either by
eavesdropping or disruption. Defending against such attacks and testing the bulletproofness of
protocols is a challenging process. This work describes attacks on SSL/TLS and implements selected
attacks within tlsfuzzer --- a sophisticated solution for testing SSL/TLS implementations. The
resulting implementation of attacks is demonstrated on three SSL/TLS implementations.

{% include gallery %}
