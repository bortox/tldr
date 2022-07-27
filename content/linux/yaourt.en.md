---
author: ['Ruben Vereecken', 'Andreas Schnebinger', 'Niklas', 'Dylan Rees']
date: 1635215179
title: "yaourt, TLDR Pages"
description: "yaourt, Arch Linux utility for building packages from the Arch User Repository."
categories: "linux"
---
> More information: <https://linuxcommandlibrary.com/man/yaourt>.

- Synchronize and update all packages (including AUR):

```bash
yaourt -Syua
```

- Install a new package (includes AUR):

```bash
yaourt -S package_name
```

- Remove a package and its dependencies (includes AUR packages):

```bash
yaourt -Rs package_name
```

- Search the package database for a keyword (including AUR):

```bash
yaourt -Ss package_name
```

- List installed packages, versions, and repositories (AUR packages will be listed under the repository name 'local'):

```bash
yaourt -Q
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Niklas](mailto:derNiklaas@users.noreply.github.com) | yank, yaourt: add more information link (#7049) | 2021-10-26T04:26:19 | [bf5c13a00d3b](https://github.com/tldr-pages/tldr/commit/bf5c13a00d3b256646326a4d3bfd23fddc5dbed3)
[Andreas Schnebinger](mailto:andi.schnebinger@googlemail.com) | yaourt: use token syntax | 2018-11-15T04:59:50 | [66bef8afb354](https://github.com/tldr-pages/tldr/commit/66bef8afb3540dfd67b0e44fa23a8b41e7cb725f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted yaourt.md | 2016-01-24T11:45:36 | [06706baf313b](https://github.com/tldr-pages/tldr/commit/06706baf313b1e09d9c1ca85b0ac7404a6c5eda1)
[Dylan Rees](mailto:dylanrees@protonmail.ch) | Update yaourt.md | 2016-01-23T00:19:17 | [22d3491ed294](https://github.com/tldr-pages/tldr/commit/22d3491ed294363d9192fe55bcb0abaa493d3e09)
[Dylan Rees](mailto:dylanrees@protonmail.ch) | Create yaourt.md | 2016-01-18T07:50:01 | [5366dade9896](https://github.com/tldr-pages/tldr/commit/5366dade9896e272fc9d6e2224836875e2f2996f)

