---
author: ['Pit Henrich']
date: 1611320266
title: "numactl, TLDR Pages"
description: "numactl, Control NUMA policy for processes or shared memory."
categories: "linux"
---
> More information: <https://man7.org/linux/man-pages/man8/numactl.8.html>.

- Run a command on node 0 with memory allocated on node 0 and 1:

```bash
numactl --cpunodebind=0 --membind=0,1 -- command command_arguments
```

- Run a command on CPUs (cores) 0-4 and 8-12 of the current cpuset:

```bash
numactl --physcpubind=+0-4,8-12 -- command command_arguments
```

- Run a command with its memory interleaved on all CPUs:

```bash
numactl --interleave=all -- command command_arguments
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pit Henrich](mailto:50917034+somefoo@users.noreply.github.com) | numactl: add page (#5167) * numactl: add page * numactl: add page fix * Apply suggestions from code review Co-authored-by: Axel [...] | 2021-01-22T13:57:46 | [fab3ebc72ae1](https://github.com/tldr-pages/tldr/commit/fab3ebc72ae1bf0144572c305fb99c514f538957)

