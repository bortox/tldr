---
author: ['Owen Voke', 'pxgamer', 'Marco Bonelli']
date: 1559564381
title: "choco pin"
description: "choco pin, Pin a package at a specific version with Chocolatey."
categories: "windows"
---
> Pinned packages are skipped automatically when upgrading.

> More information: <https://chocolatey.org/docs/commands-pin>.

- Display a list of pinned packages and their versions:

```bash
choco pin list
```

- Pin a package at its current version:

```bash
choco pin add --name package
```

- Pin a package at a specific version:

```bash
choco pin add --name package --version version
```

- Remove a pin for a specific package:

```bash
choco pin remove --name package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | choco-pin: add link to homepage | 2019-03-20T06:53:44 | [1888af5f5239](https://github.com/tldr-pages/tldr/commit/1888af5f5239445b864d9edeed5a5da9389099fc)
[Owen Voke](mailto:owzie123@gmail.com) | choco-pin: add page (#2037) * choco-pin: add page * choco-pin: update list example description | 2018-03-24T15:23:24 | [75a071c25070](https://github.com/tldr-pages/tldr/commit/75a071c25070e7b7d33f1c470f6f1ccf9261c88c)

