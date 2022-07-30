---
author: ['toydotgame']
date: 1652704197
title: "cpupower"
description: "cpupower, Tools regarding CPU power and tuning options."
categories: "linux"
---
> This command is available as part of the `cpupower` package, or as part of `kernel-tools` on Fedora.

> More information: <https://manned.org/cpupower>.

- List CPUs:

```bash
sudo cpupower --cpu all info
```

- Print information about all cores:

```bash
sudo cpupower --cpu all info
```

- Set all CPUs to a power-saving frequency governor:

```bash
sudo cpupower --cpu all frequency-set --governor powersave
```

- Print CPU 0's available frequency [g]overnors:

```bash
sudo cpupower --cpu 0 frequency-info g | grep "analyzing\|governors"
```

- Print CPU 4's frequency from the hardware, in a human-readable format:

```bash
sudo cpupower --cpu 4 frequency-info --hwfreq --human
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[toydotgame](mailto:64190512+toydotgame@users.noreply.github.com) | cpupower: add page (#8073) | 2022-05-16T14:29:57 | [6e60a5fd2d38](https://github.com/tldr-pages/tldr/commit/6e60a5fd2d387332435c6590c4ca32085e84ecc5)

