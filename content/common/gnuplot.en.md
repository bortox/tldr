---
author: ['Schneider', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1559564381
title: "gnuplot"
description: "gnuplot, A graph plotter that outputs in several formats."
categories: "common"
---
> More information: <http://www.gnuplot.info/>.

- Start the interactive graph plotting shell:

```bash
gnuplot
```

- Plot the graph for the specified graph definition file:

```bash
gnuplot path/to/definition.plt
```

- Set the output format by executing a command before loading the definition file:

```bash
gnuplot -e "set output "path/to/filename.png" size 1024,768" path/to/definition.plt
```

- Persist the graph plot preview window after gnuplot exits:

```bash
gnuplot --persist path/to/definition.plt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | gnuplot.md add homepage | 2019-04-11T09:49:15 | [b542b11ad102](https://github.com/tldr-pages/tldr/commit/b542b11ad10271a0abbf8a423855604d4d822354)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | gnuplot: add page (#2088) | 2018-05-07T02:33:42 | [cf12bb9f0425](https://github.com/tldr-pages/tldr/commit/cf12bb9f04250715d0b4419ddce096d3d7ecca9c)

