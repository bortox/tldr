---
author: ['Julia Evans', 'Marco Bonelli', 'lbonanomi', 'Adrien Thebo']
date: 1652916946
title: "nsenter"
description: "nsenter, Run a new command in a running process' namespace."
categories: "linux"
---
> Particularly useful for docker images or chroot jails.

> More information: <https://manned.org/nsenter>.

- Run a specific command using the same namespaces as an existing process:

```bash
nsenter --target pid --all command command_arguments
```

- Run a specific command in an existing process's network namespace:

```bash
nsenter --target pid --net command command_arguments
```

- Run a specific command in an existing process's PID namespace:

```bash
nsenter --target pid --pid command command_arguments
```

- Run a specific command in an existing process's IPC namespace:

```bash
nsenter --target pid --ipc command command_arguments
```

- Run a specific command in an existing process's UTS, time, and IPC namespaces:

```bash
nsenter --target pid --uts --time --ipc -- command command_arguments
```

- Run a specific command in an existing process's namespace by referencing procfs:

```bash
nsenter --pid=/proc/pid/pid/net -- command command_arguments
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrien Thebo](mailto:adrien@lagrange-automation.io) | nsenter: add namespaces examples (#8084) add examples for multiple namespaces, procfs specified namespace | 2022-05-19T01:35:46 | [59e789fc735d](https://github.com/tldr-pages/tldr/commit/59e789fc735d95c187d297139d7b7ff6eb0bf4db)
[Julia Evans](mailto:julia@jvns.ca) | nsenter: add --all example and refresh (#8003) | 2022-05-08T23:26:45 | [39afceec309c](https://github.com/tldr-pages/tldr/commit/39afceec309ca682be04d18d1e6e4fee4e77276e)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | nsenter: add page (#2958) | 2019-04-30T12:12:26 | [d8c9c5a18a46](https://github.com/tldr-pages/tldr/commit/d8c9c5a18a4638b5537127a3adb1c399eb9b081c)

