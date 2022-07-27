---
author: ['Mario Álvarez', 'Seth Falco', 'lincc']
date: 1632422063
title: "leave, TLDR Pages"
description: "leave, Set a reminder for when it's time to leave."
categories: "common"
---
> To remove reminders use `kill $(pidof leave)`.

> More information: <https://www.freebsd.org/cgi/man.cgi?query=leave>.

- Set a reminder at a given time:

```bash
leave time_to_leave
```

- Set a reminder to leave at noon:

```bash
leave 1200
```

- Set a reminder in a specific amount of time:

```bash
leave +amount_of_time
```

- Set a reminder to leave in 4 hours and 4 minutes:

```bash
leave +0404
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | common/l*: add more information link (#6577) | 2021-09-23T20:34:23 | [35d3601e388a](https://github.com/tldr-pages/tldr/commit/35d3601e388ad4b54affea092d6dd4f0a8be37d2)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Mario Álvarez](mailto:m4grio@users.noreply.github.com) | leave: add page (#1574) | 2017-10-29T07:23:36 | [59de62110cd2](https://github.com/tldr-pages/tldr/commit/59de62110cd247a2c6f8838c17e10c1ecb5d1aa8)

