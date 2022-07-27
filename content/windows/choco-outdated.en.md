---
author: ['Marco Bonelli', 'pxgamer', 'Owen Voke']
date: 1559564381
title: "choco outdated, TLDR Pages"
description: "choco outdated, Check for outdated packages with Chocolatey."
categories: "windows"
---
> More information: <https://chocolatey.org/docs/commands-outdated>.

- Display a list of outdated packages in table format:

```bash
choco outdated
```

- Ignore pinned packages in the output:

```bash
choco outdated --ignore-pinned
```

- Specify a custom source to check packages from:

```bash
choco outdated --source source_url|alias
```

- Provide a username and password for authentication:

```bash
choco outdated --user username --password password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | choco-outdated: add link to homepage | 2019-03-20T06:53:44 | [43fb1f26d962](https://github.com/tldr-pages/tldr/commit/43fb1f26d962818567291c92d94fbd9c11b894f7)
[Owen Voke](mailto:owzie123@gmail.com) | choco-outdated: add page (#2032) | 2018-03-18T13:51:48 | [6832c97b3196](https://github.com/tldr-pages/tldr/commit/6832c97b31968ff5a08c7478a128313f266a41d2)

