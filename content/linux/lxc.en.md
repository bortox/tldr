---
author: ['Damian Peterson', 'Lucas Gabriel Schneider', 'adrian5']
date: 1629110041
title: "lxc, TLDR Pages"
description: "lxc, Manage Linux containers using the lxd REST API."
categories: "linux"
---
> Any container names or patterns can be prefixed with the name of a remote server.

> More information: <https://manned.org/lxc>.

- List local containers matching a string. Omit the string to list all local containers:

```bash
lxc list match_string
```

- List images matching a string. Omit the string to list all images:

```bash
lxc image list [remote:]match_string
```

- Create a new container from an image:

```bash
lxc init [remote:]image container
```

- Start a container:

```bash
lxc start [remote:]container
```

- Stop a container:

```bash
lxc stop [remote:]container
```

- Show detailed info about a container:

```bash
lxc info [remote:]container
```

- Take a snapshot of a container:

```bash
lxc snapshot [remote:]container snapshot
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[adrian5](mailto:adrian5@users.noreply.github.com) | lxc: change container creation command | 2019-09-28T21:36:34 | [74a9a93e147a](https://github.com/tldr-pages/tldr/commit/74a9a93e147a057476a020552561368889983a61)
[Damian Peterson](mailto:damian@peterson.nz) | lxc: add page (#1371) | 2017-05-16T07:12:11 | [9fbc74e1de45](https://github.com/tldr-pages/tldr/commit/9fbc74e1de4537ffd9f649257d64b997f789cd5a)

