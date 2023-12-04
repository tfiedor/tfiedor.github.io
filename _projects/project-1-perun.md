---
title: "Perun: Light-weight Performance Version System"
excerpt: "An open source light-weight Performance Version System and tool suite of performance
analysis and profiling tools."
collection: projects
github: "https://github.com/Perfexionists/perun"
pypi: "https://pypi.org/project/perun-toolsuite/"
tags:
  - performance testing
  - performance analysis
  - profiling
  - fuzz testing
  - tool suite
gallery:
---

[![build status](https://github.com/Perfexionists/perun/actions/workflows/ubuntu.yml/badge.svg)](https://github.com/Perfexionists/perun/actions)
[![codecov](https://codecov.io/gh/Perfexionists/perun/graph/badge.svg?token=3x4Luodr84)](https://codecov.io/gh/Perfexionists/perun)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/a704486b4679442cb2a53173475f79ca)](https://app.codacy.com/gh/Perfexionists/perun/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Maintainability](https://api.codeclimate.com/v1/badges/1e47ad63527d8d2e14c3/maintainability)](https://codeclimate.com/github/Perfexionists/perun/maintainability)
[![GitHub tag](https://img.shields.io/github/tag/Perfexionists/perun.svg)](https://github.com/Perfexionists/perun)

|       |                                                                                                 |
|-------|-------------------------------------------------------------------------------------------------|
| Demo  | [fit.vutbr.cz/perun-demo](https://www.fit.vutbr.cz/research/groups/verifit/tools/perun-demo/)   |
| Github | [Perfexionists/perun](https://github.com/Perfexionists/perun)                                  |
| PyPi  | [pypi/perun-toolsuite](https://pypi.org/project/perun-toolsuite/)                               |

[<i class="fab fa-fw fa-github zoom" aria-hidden="true"></i> More on github!](https://github.com/Perfexionists/perun)

## My contributions

1. I am the main author and developer of the Perun. I created the whole infrastructure and main modules. I optimized and
   refactored almost every module in the Perun.
2. I supervised (or co-supervised together with Jirka Pavela, who is currently the main supervisor of students) all the
   work done around Perun.
3. I am the main idea-maker of our Perfexionist group, and I am lucky I had talented students to polish and greatly
   expand on these ideas.

I am still **active** developer of the Perun (though my activity varies).

## Installation

To install `perun` from the repository, run the following:

```shell
git clone https://github.com/tfiedor/perun.git
cd perun
make install
```

Alternatively, you can install Perun from PyPI using the following:

```shell
pip install perun-toolsuite
```

If you encounter any problems with installing `perun`, please refer to
the [README](https://github.com/Perfexionists/perun/blob/devel/README.md).

## Overview

Perun is an open source light-weight Performance Version System, which works as a wrapper over
existing Version Control Systems and in parallel manages performance profiles corresponding to
different versions of projects. Moreover, it offers a tool suite suitable for automation of the
performance regression test runs, postprocessing of existing profiles or effective interpretation
of the results.

## Licence

The code in this project is licensed under GNU GPLv3 license.

## Other contributors

### The Core and Original Perfexionists Group

- **Tomáš Fiedor** ([tfiedor](https://github.com/tfiedor), [TomasFiedor@gmail.com](mailto:tomasfiedor@github.com)): main developer of Perun, the leader of Perfexionists.
- **Jiří Pavela** ([JiriPavela](https://github.com/JiriPavela), [Jirka.Pavela@gmail.com](mailto:jirka.pavela@github.com)): second-in-command of Perun; main developer of `trace`.
- **Radim Podola**: original co-author of Perun, main author of `memory` profiler and selected visualizations.
- **Šimon Stupinský**: main developer of non-parametric models.
- **Matúš Liščinský**: main developer of performance fuzzing and performance blowing.
- **Peter Močáry**: main developer of PIN engine for `trace` collector.
- **Ondřej Míchal**: main developer of experimental profiler of energy consumption;
- **Vojtěch Hájek**: main developer of C# profiler.
- **Martina Grzybowská**: created awesome (sadly unmerged) GUI for Perun.

### Special Thanks To

-   **Jan Fiedor** (Honeywell)---for feedback, and technical discussions;
-   **Jirka Hladký** and his team (RedHat)---for technical discussions;
-   **Martin Hruška** (BUT FIT)---for feedback, and technical discussions;
-   **Michal Kotoun** (BUT FIT)---for feedback, and having faith in this repo;
-   **Viktor Malík** (Red Hat)---for support.
-   **Petr Müller** (Red Hat)---for nice discussion about the project;
-   **Hanka Pluháčková (Šimková)** (Mavenir, ex-BUT FIT)---for awesome logo, theoretical discussions about statistics, feedback, and lots of ideas;
-   **Adam Rogalewicz** (BUT FIT)---for support, theoretical discussions, feedback;
-   **Tomas Vojnar** (BUT FIT)---for support, theoretical discussions, feedback;
-   **Jan Zelený** (Red Hat)---for awesome support, and feedback.
