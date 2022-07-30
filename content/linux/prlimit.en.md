---
author: ['endorama']
date: 1642423217
title: "prlimit"
description: "prlimit, Get or set process resource soft and hard limits."
categories: "linux"
---
> Given a process ID and one or more resources, prlimit tries to retrieve and/or modify the limits.

> More information: <https://manned.org/prlimit>.

- Display limit values for all current resources for the running parent process:

```bash
prlimit
```

- Display limit values for all current resources of a specified process:

```bash
prlimit --pid pid number
```

- Run a command with a custom number of open files limit:

```bash
prlimit --nofile=10 command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[endorama](mailto:526307+endorama@users.noreply.github.com) | prlimit: add page (#7113) | 2022-01-17T13:40:17 | [dfbf2f5bce88](https://github.com/tldr-pages/tldr/commit/dfbf2f5bce887b3c95248e5bb8f3b7bf8a29acbe)

