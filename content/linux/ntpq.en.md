---
author: ['RH-sdavey']
date: 1619369260
title: "ntpq"
description: "ntpq, Query the Network Time Protocol (NTP) daemon."
categories: "linux"
---
> More information: <https://www.eecis.udel.edu/~mills/ntp/html/ntpq.html>.

- Start `ntpq` in interactive mode:

```bash
ntpq --interactive
```

- Print a list of NTP peers:

```bash
ntpq --peers
```

- Print a list of NTP peers without resolving hostnames from IP addresses:

```bash
ntpq --numeric --peers
```

- Use `ntpq` in debugging mode:

```bash
ntpq --debug-level
```

- Print NTP system variables values:

```bash
ntpq --command=rv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[RH-sdavey](mailto:32485509+RH-sdavey@users.noreply.github.com) | chronyc, ntpq: add page (#5828) | 2021-04-25T18:47:40 | [c5ceab51bb3d](https://github.com/tldr-pages/tldr/commit/c5ceab51bb3de622648fcb74f562d1aa91c85ee3)

