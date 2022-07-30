---
author: ['Owen Voke', 'bl-ue', 'pxgamer', 'Marco Bonelli']
date: 1621541621
title: "choco new"
description: "choco new, Generate new package specification files with Chocolatey."
categories: "windows"
---
> More information: <https://chocolatey.org/docs/commands-new>.

- Create a new package skeleton:

```bash
choco new package_name
```

- Create a new package with a specific version:

```bash
choco new package_name --version version
```

- Create a new package with a specific maintainer name:

```bash
choco new package_name --maintainer maintainer_name
```

- Create a new package in a custom output directory:

```bash
choco new package_name --output-directory path/to/directory
```

- Create a new package with specific 32-bit and 64-bit installer URLs:

```bash
choco new package_name url="url" url64="url"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | choco-new: add link to homepage | 2019-03-20T06:53:44 | [77380f8a6358](https://github.com/tldr-pages/tldr/commit/77380f8a63580bb23d3458869b7158fcccf8dcc6)
[Owen Voke](mailto:owzie123@gmail.com) | choco-new: add page (#2049) | 2018-03-29T18:03:34 | [a6b0c40794fc](https://github.com/tldr-pages/tldr/commit/a6b0c40794fcddb63435dc088bd26d9cc4e9a2b9)

