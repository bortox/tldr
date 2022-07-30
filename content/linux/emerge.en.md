---
author: ['Ruben Vereecken', 'rprieto', 'Stig124', 'Agniva De Sarker']
date: 1625841955
title: "emerge"
description: "emerge, Gentoo Linux package manager utility."
categories: "linux"
---
> More information: <https://wiki.gentoo.org/wiki/Portage#emerge>.

- Synchronize all packages:

```bash
emerge --sync
```

- Update all packages, including dependencies:

```bash
emerge -uDNav @world
```

- Resume a failed updated, skipping the failing package:

```bash
emerge --resume --skipfirst
```

- Install a new package, with confirmation:

```bash
emerge -av package_name
```

- Remove a package, with confirmation:

```bash
emerge -Cav package_name
```

- Remove orphaned packages (that were installed only as dependencies):

```bash
emerge -avc
```

- Search the package database for a keyword:

```bash
emerge -S keyword
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

