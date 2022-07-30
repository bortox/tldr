---
author: ['Stig124', 'Severin Fürbringer']
date: 1625841955
title: "equery"
description: "equery, View information about Portage packages."
categories: "linux"
---
> More information: <https://wiki.gentoo.org/wiki/Equery>.

- List all installed packages:

```bash
equery list '*'
```

- Search for installed packages in the Portage tree and in overlays:

```bash
equery list -po package_name
```

- List all packages that depend on a given package:

```bash
equery depends package_name
```

- List all packages that a given package depends on:

```bash
equery depgraph package_name
```

- List all files installed by a package:

```bash
equery files --tree package_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Severin Fürbringer](mailto:severin@protonmail.ch) | equery: add page (#920) | 2016-06-21T23:53:23 | [a358006f0468](https://github.com/tldr-pages/tldr/commit/a358006f0468b5941858128801bacfd4ae88bf68)

