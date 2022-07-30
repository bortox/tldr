---
author: ['Schneider', 'dathide', 'Emily Grace Seville', 'lbonanomi']
date: 1647882468
title: "taskset"
description: "taskset, Get or set a process' CPU affinity or start a new process with a defined CPU affinity."
categories: "linux"
---
> More information: <https://manned.org/taskset>.

- Get a running process' CPU affinity by PID:

```bash
taskset --pid --cpu-list pid
```

- Set a running process' CPU affinity by PID:

```bash
taskset --pid --cpu-list cpu_id pid
```

- Start a new process with affinity for a single CPU:

```bash
taskset --cpu-list cpu_id command
```

- Start a new process with affinity for multiple non-sequential CPUs:

```bash
taskset --cpu-list cpu_id_1,cpu_id_2,cpu_id_3
```

- Start a new process with affinity for CPUs 1 through 4:

```bash
taskset --cpu-list cpu_id_1-cpu_id_4
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[dathide](mailto:47128084+dathide@users.noreply.github.com) | Fix syntax (#7543) Fix the syntax for running on non-sequential CPUs, which is done with commas. Also fix the syntax for running on [...] | 2021-12-16T03:45:58 | [b205ef3b38e9](https://github.com/tldr-pages/tldr/commit/b205ef3b38e93beba0df681d61ea03e1218df679)
[Schneider](mailto:lucas.schneider@sap.com) | multiple pages: remove trailing whitespaces | 2020-03-12T20:52:09 | [b3682af6ff3b](https://github.com/tldr-pages/tldr/commit/b3682af6ff3b8e0de63583ce18893847600bdf22)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | taskset: add page (#2942) | 2019-04-25T18:58:40 | [322519512b10](https://github.com/tldr-pages/tldr/commit/322519512b109c0836a18013d78bd9bbd4f8f4a2)

