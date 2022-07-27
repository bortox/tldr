---
author: ['RH-sdavey']
date: 1619369260
title: "chronyc, TLDR Pages"
description: "chronyc, Query the Chrony NTP daemon."
categories: "linux"
---
> More information: <https://chrony.tuxfamily.org/doc/4.0/chronyc.html>.

- Start chronyc in interactive mode:

```bash
chronyc
```

- Display tracking stats for the Chrony daemon:

```bash
chronyc tracking
```

- Print the time sources that Chrony is currently using:

```bash
chronyc sources
```

- Display stats for sources currently used by chrony daemon as a time source:

```bash
chronyc sourcestats
```

- Step the system clock immediately, bypassing any slewing:

```bash
chronyc makestep
```

- Display verbose information about each NTP source:

```bash
chronyc ntpdata
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[RH-sdavey](mailto:32485509+RH-sdavey@users.noreply.github.com) | chronyc, ntpq: add page (#5828) | 2021-04-25T18:47:40 | [c5ceab51bb3d](https://github.com/tldr-pages/tldr/commit/c5ceab51bb3de622648fcb74f562d1aa91c85ee3)

