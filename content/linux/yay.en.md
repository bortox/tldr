---
author: ['Axel Navarro', 'MasterTos', 'Snehit Sah', 'Pierre Depaz']
date: 1628946438
title: "yay"
description: "yay, Yet Another Yogurt: A utility for Arch Linux to build and install packages from the Arch User Repository."
categories: "linux"
---
> Also see `pacman`.

> More information: <https://github.com/Jguer/yay>.

- Interactively search and install packages from the repos and AUR:

```bash
yay package_name|search_term
```

- Synchronize and update all packages from the repos and AUR:

```bash
yay
```

- Synchronize and update only AUR packages:

```bash
yay -Sua
```

- Install a new package from the repos and AUR:

```bash
yay -S package_name
```

- Remove an installed package and both its dependencies and configuration files:

```bash
yay -Rns package_name
```

- Search the package database for a keyword from the repos and AUR:

```bash
yay -Ss keyword
```

- Remove orphaned packages (installed as dependencies but not required by any package):

```bash
yay -Yc
```

- Show statistics for installed packages and system health:

```bash
yay -Ps
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Snehit Sah](mailto:snehitsah@protonmail.com) | yay: add -Yc example (#6324) | 2021-08-14T15:07:18 | [530fc91ea8ba](https://github.com/tldr-pages/tldr/commit/530fc91ea8ba78e34fb6d5f8d9ff11c0a898c125)
[Pierre Depaz](mailto:pierre.depaz@gmail.com) | yay: add -Rns example (#5486) | 2021-03-25T13:31:09 | [3e227f7ae0b4](https://github.com/tldr-pages/tldr/commit/3e227f7ae0b439b967617e34d5011bb89908fb26)
[Axel Navarro](mailto:navarroaxel@gmail.com) | yay: add more information link (#5387) | 2021-03-08T21:16:15 | [16a149376348](https://github.com/tldr-pages/tldr/commit/16a149376348b5a91d473c9b064cd319727096b6)
[MasterTos](mailto:MasterTos@yahoo.com) | yay: add page (#2460) | 2018-10-28T18:12:49 | [99ecfb405480](https://github.com/tldr-pages/tldr/commit/99ecfb405480be1b286cd5bc3049abea2cc799dc)

