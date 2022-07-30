---
author: ['Balázs Úr', 'Stig124', 'Seth Falco', 'Severin Fürbringer']
date: 1629050349
title: "fallocate"
description: "fallocate, Reserve or deallocate disk space to files."
categories: "linux"
---
> The utility allocates space without zeroing.

> More information: <https://manned.org/fallocate>.

- Reserve a file taking up 700 MiB of disk space:

```bash
fallocate --length 700M path/to/file
```

- Shrink an already allocated file by 200 MiB:

```bash
fallocate --collapse-range --length 200M path/to/file
```

- Shrink 20 MB of space after 100 MiB in a file:

```bash
fallocate --collapse-range --offset 100M --length 20M path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[Severin Fürbringer](mailto:severin@protonmail.ch) | fallocate: add page (#2089) | 2018-05-06T15:08:41 | [57849426b381](https://github.com/tldr-pages/tldr/commit/57849426b38168340c442faadd01aeff4c64c0e1)

