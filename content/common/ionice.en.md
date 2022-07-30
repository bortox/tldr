---
author: ['kumon', 'Kyle', 'Ruben Vereecken']
date: 1629747204
title: "ionice"
description: "ionice, Get or set program I/O scheduling class and priority."
categories: "common"
---
> Scheduling classes: 1 (realtime), 2 (best-effort), 3 (idle).

> Priority levels: 0 (the highest) - 7 (the lowest).

> More information: <https://manned.org/ionice>.

- Set I/O scheduling class of a running process:

```bash
ionice -c scheduling_class -p pid
```

- Run a command with custom I/O scheduling class and priority:

```bash
ionice -c scheduling_class -n priority command
```

- Print the I/O scheduling class and priority of a running process:

```bash
ionice -p pid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[kumon](mailto:kumon0587@gmail.com) | improve description | 2016-01-05T11:45:42 | [3d6b4aed47c5](https://github.com/tldr-pages/tldr/commit/3d6b4aed47c5bc3acf3309f016988f8475a46aeb)
[kumon](mailto:kumon0587@gmail.com) | Add class & level details and update usage. | 2016-01-05T03:24:03 | [53ac09746b18](https://github.com/tldr-pages/tldr/commit/53ac09746b185734c0d0888535c37c3585a2ce0f)
[kumon](mailto:kumon0587@gmail.com) | Added ionice | 2016-01-04T16:15:09 | [2827f15c69f9](https://github.com/tldr-pages/tldr/commit/2827f15c69f924e6a3b2fcf13dcade24f1092cc6)

