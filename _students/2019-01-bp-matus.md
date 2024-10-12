---
title: "Matúš Liščinský: Fuzz Testing of Program Performance"
collection: students
type: "Bachelors's Thesis"
permalink: /students/2019-01-bp-matus
excerpt: 'Disclaimer: While this thesis was officially supervised by Adam Rogalewicz (due some internal restrictions), I
was the main supervisor of this whole thesis. The goal of this thesis was to extend the notion of performance
fuzztesting to more fine-tuned (custom) rules and more performance-based evaluation.
The resulting fuzzer is part of Perun and provides new ideas (sadly unpublished).'
paperurl: 'http://tfiedor.github.io/files/thesis/matus-bp.pdf'
tags:
  - perun
  - performance fuzzing
  - fuzzing
gallery:
  - url: students/matus-bp-1.JPG
    image_path: students/matus-bp-1.JPG
    alt: "an example result of performance fuzzing for program demonstrating ReDoS attack"
    alt: "An example result of performance fuzzing for program demonstrating ReDoS attack."
---

|                      |                                                                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Thesis Detail        | [Institution site](https://www.vut.cz/studenti/zav-prace/detail/121838) |
| Thesis Download      | [Thesis Download](https://www.vut.cz/www_base/zav_prace_soubor_verejne.php?file_id=197106) |

Disclaimer: While this thesis was officially supervised by Adam Rogalewicz (due some internal restrictions), I
was the main supervisor of this whole thesis. The goal of this thesis was to extend the notion of performance
fuzztesting to more fine-tuned (custom) rules and more performance-based evaluation.
The resulting fuzzer is part of Perun and provides new ideas (sadly unpublished).

## Abstract

Fixing one issue sometimes brings another ten to the program. To detect these issues, especially
performance issues, we often have to supply the program with input, that forces its worst-case
behaviour. A popular solution to automatic inputs generation is so called fuzzing, however, its
intention is to find functional bugs. In this work, we aim to construct an automatic generator of
inputs whose task will be to trigger performance fluctuations. So we propose to tune fuzzing
mutation rules and ways of processing the information about program run, to particularly trigger
the performance bugs. We integrate our solution into a performance profile manager Perun, which
stores information about every run as a profile and is able to compare these profiles to check for
performance change. Therefore we can prove that executing with certain input takes more time or
memory. We tested our fuzzer on several artificial projects, which shows its potential with
generated inputs that prolong the runtime of the program. Such a solution would allow developers to
regularly test every version of a project for performance bugs and avoid them completely by
automatically finding new exhausting inputs before release.

{% include gallery %}
