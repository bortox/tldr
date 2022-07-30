---
author: ['Natechawin Suthison', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629110041
title: "mcookie"
description: "mcookie, Generates random 128-bit hexadecimal numbers."
categories: "linux"
---
> More information: <https://manned.org/mcookie>.

- Generate a random number:

```bash
mcookie
```

- Generate a random number, using the contents of a file as a seed for the randomness:

```bash
mcookie --file path/to/file
```

- Generate a random number, using a specific number of bytes from a file as a seed for the randomness:

```bash
mcookie --file path/to/file --max-size number_of_bytes
```

- Print the details of the randomness used, such as the origin and seed for each source:

```bash
mcookie --verbose
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Natechawin Suthison](mailto:natechawin@gmail.com) | mcookie: add page (#3322) | 2019-10-10T19:40:57 | [8de5a4ca77f5](https://github.com/tldr-pages/tldr/commit/8de5a4ca77f5d46e99e61be2afb3b3f24b32c9f8)

