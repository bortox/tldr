---
author: ['Owen Voke', 'Stig124']
date: 1625841955
title: "ebuild"
description: "ebuild, A low level interface to the Gentoo Portage system."
categories: "linux"
---
> More information: <https://wiki.gentoo.org/wiki/Ebuild>.

- Create or update the package manifest:

```bash
ebuild path/to/file.ebuild manifest
```

- Clean the temporary build directories for the build file:

```bash
ebuild path/to/file.ebuild clean
```

- Fetch sources if they do not exist:

```bash
ebuild path/to/file.ebuild fetch
```

- Extract the sources to a temporary build directory:

```bash
ebuild path/to/file.ebuild unpack
```

- Compile the extracted sources:

```bash
ebuild path/to/file.ebuild compile
```

- Install the package to a temporary install directory:

```bash
ebuild path/to/file.ebuild install
```

- Install the temporary files to the live filesystem:

```bash
ebuild path/to/file.ebuild qmerge
```

- Fetch, unpack, compile, install and qmerge the specified ebuild file:

```bash
ebuild path/to/file.ebuild merge
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Owen Voke](mailto:owzie123@gmail.com) | ebuild: add page (#2075) | 2018-05-10T21:51:14 | [aec42631133d](https://github.com/tldr-pages/tldr/commit/aec42631133d17e6511bef751020ad4e484089e5)

