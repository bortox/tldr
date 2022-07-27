---
author: ['Seth Falco', 'bl-ue']
date: 1629050349
title: "git count-objects, TLDR Pages"
description: "git count-objects, Count the number of unpacked objects and their disk consumption."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-count-objects>.

- Count all objects and display the total disk usage:

```bash
git count-objects
```

- Display a count of all objects and their total disk usage, displaying sizes in human-readable units:

```bash
git count-objects --human-readable
```

- Display more verbose information:

```bash
git count-objects --verbose
```

- Display more verbose information, displaying sizes in human-readable units:

```bash
git count-objects --human-readable --verbose
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-count-objects: add page (#5114) | 2021-01-16T16:43:31 | [1f6db5a93402](https://github.com/tldr-pages/tldr/commit/1f6db5a9340263fb929a41ad7e42a7db84e59717)

