---
author: ['CleanMachine1', 'Rowan Freeman']
date: 1624920504
title: "trizen, TLDR Pages"
description: "trizen, Arch Linux utility for building packages from the Arch User Repository (AUR)."
categories: "linux"
---
> More information: <https://github.com/trizen/trizen>.

- Synchronize and update all AUR packages:

```bash
trizen -Syua
```

- Install a new package:

```bash
trizen -S package
```

- Remove a package and its dependencies:

```bash
trizen -Rs package
```

- Search the package database for a keyword:

```bash
trizen -Ss keyword
```

- Show information about a package:

```bash
trizen -Si package
```

- List installed packages and versions:

```bash
trizen -Qe
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/t*: add information link (#6166) | 2021-06-29T00:48:24 | [d86d3d6206bd](https://github.com/tldr-pages/tldr/commit/d86d3d6206bdf76257ce480be4a8a71d2d4fdda6)
[Rowan Freeman](mailto:rowanfreeman@users.noreply.github.com) | trizen: new page (#1955) | 2018-02-03T11:55:17 | [562dbba04540](https://github.com/tldr-pages/tldr/commit/562dbba04540dc91f522f54246ea2a60d0f68380)

