---
author: ['Seth Falco', 'marchersimon']
date: 1629050349
title: "pio system, TLDR Pages"
description: "pio system, Miscellaneous system commands for PlatformIO."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/system/>.

- Install shell completion for the current shell (supports Bash, Fish, Zsh and PowerShell):

```bash
pio system completion install
```

- Uninstall shell completion for the current shell:

```bash
pio system completion uninstall
```

- Display system-wide PlatformIO information:

```bash
pio system info
```

- Remove unused PlatformIO data:

```bash
pio system prune
```

- Remove only cached data:

```bash
pio system prune --cache
```

- List unused PlatformIO data that would be removed but do not actually remove it:

```bash
pio system prune --dry-run
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:marchersimon@zohomail.eu) | remove index.html from more information links where posible | 2021-04-11T17:29:10 | [1e2f4f202a9e](https://github.com/tldr-pages/tldr/commit/1e2f4f202a9e7827b670bd2db5d1cb776316df06)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-system: add page (#5523) | 2021-03-28T20:31:07 | [e7cf9014c0f2](https://github.com/tldr-pages/tldr/commit/e7cf9014c0f2bc0297abec2473c6fd243c146909)

