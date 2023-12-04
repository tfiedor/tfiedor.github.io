---
title: "Mata: The Automata Library"
excerpt: "Mata is an open source automata library that offers interface for different kinds of automata (NFA)."
collection: projects
github: "https://github.com/VeriFIT/mata"
pypi: "https://pypi.org/project/libmata/"
tags:
  - finite automata
  - library
gallery:
---

[![GitHub tag](https://img.shields.io/github/tag/VeriFIT/mata.svg)](https://github.com/VeriFIT/mata)
[![Quality](https://github.com/VeriFIT/mata/actions/workflows/code-quality.yml/badge.svg)](https://github.com/VeriFIT/mata/actions/workflows/code-quality.yml)
[![Python-Binding (build-&-test)](https://github.com/VeriFIT/mata/actions/workflows/python-binding.yml/badge.svg?branch=devel)](https://github.com/VeriFIT/mata/actions/workflows/python-binding.yml)
[![codecov](https://codecov.io/gh/VeriFIT/mata/branch/devel/graph/badge.svg?token=9VAVD19N4D)](https://codecov.io/gh/VeriFIT/mata)


|                  |                                                    |
|------------------|----------------------------------------------------|
| Github           | [Verifit/libmata](https://github.com/VeriFIT/mata) |
| PyPi             | [pypi/libmata](https://pypi.org/project/libmata/)  |

[<i class="fab fa-fw fa-github zoom" aria-hidden="true"></i> More on github!](https://github.com/VeriFIT/mata)

## My contributions

1. I was the main developer of the Python binding (David Chocholatý took over from me), which is *almost* as efficient
   as the native C/C++ library.
2. I took care of the DevOps aspects of the libmata: CI/CD (in form of github actions), testing, performance testing,
   documentation generation, and many other aspects.
3. I was one of the main reviewers of the code, assuring for the quality of the code.
4. I was the main designer for the experimental evaluation: how the benchmarks were run, how the benchmarks were
   evaluated, and how the results were presented (currently unpublished). I also created a replication package for
   evaluating the strenghts of our library.

I am currently **inactive** (rather a passive watcher) developer of the `libmata`.

## Installation

To install the `libmata`, run the following:

```shell
git clone https://github.com/VeriFIT/mata
cd mata
make release
```

To install Python binding (ready to use in Python interpreter) run the following:

```shell
pip install libmata
```

You can check out either our C/C++ examples (at [examples](https://github.com/VeriFIT/mata/tree/devel/examples)
directory) or our Jupyter notebookes (
at [examples/notebooks](https://github.com/VeriFIT/mata/tree/devel/examples/notebooks) directory).

Note, that we suggest to use virtual environment for installation from `pip`.

If you encounter any problems with installing `libmata`, please refer to
the [README](https://github.com/VeriFIT/mata/blob/devel/README.md).

## Overview

Mata is an open source automata library that offers interface for different kinds of automata (NFA, etc.). Currently,
Mata offers two interfaces:

  1. An efficient library implemented in C/C++
  2. A flexible wrapper implemented in Python that uses the efficient library

## Licence

The code of Mata is licensed under MIT licence.

## Other contributors

This list reflects only the core team around Mata, and it may be incomplete.

For a list of all people who have contributed to the codebase, see
[GitHub's list of contributors](https://github.com/VeriFIT/mata/graphs/contributors).

### The Core Mata Group

- **Lukáš Holík** ([kilohsakul](https://github.com/kilohsakul), [holik@fit.vut.cz](mailto:holik@fit.vut.cz)): the supreme leader, the emperor of theory;
- **Ondřej Lengál** ([ondrik](https://github.com/ondrik), [lengal@fit.vut.cz](mailto:lengal@fit.vut.cz)): prototype developer and the world's tallest hobbit;
- **David Chocholatý** ([Adda0](https://github.com/Adda0), [chocholaty.david@protonmail.com](mailto:chocholaty.david@protonmail.com)): library maintainer;
- **Tomáš Fiedor** ([tfiedor](https://github.com/tfiedor), [ifiedortom@fit.vut.cz](mailto:ifiedortom@fit.vut.cz)): python binding maintainer;
- **Juraj Síč** ([jurajsic](https://github.com/jurajsic), [sicjuraj@fit.vut.cz](mailto:sicjuraj@fit.vut.cz)): library developer;
- **Vojtěch Havlena** ([vhavlena](https://github.com/vhavlena/), [ihavlena@fit.vut.cz](mailto:ihavlena@fit.vut.cz)): library developer;
- **Martin Hruška** ([martinhruska](https://github.com/martinhruska), [ihruska@fit.vut.cz](mailto:ihruska@fit.vut.cz)): library design advisor, former library developer;
- **Tomáš Vojnar** ([vojnar](https://github.com/vojnar), [vojnar@fit.vut.cz](mailto:vojnar@fit.vut.cz)): the spiritual leader;

### Special Thanks To

- Tomáš Kocourek ([kocotom](https://github.com/kocotom/), [kocotom@seznam.cz](mailto:kocotom@seznam.cz)): library developer for first AFA design;
- Michal Horký ([MichalHorky](https://github.com/MichalHorky), [horky-michal@seznam.cz](mailto:horky-michal@seznam.cz)): RE2 parser interface developer;