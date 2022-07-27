---
author: ['Davi', 'Ben Lönnqvist', 'Ishaan Bhimwal', 'bl-ue']
date: 1658240132
title: "paru, TLDR Pages"
description: "paru, An AUR helper and pacman wrapper."
categories: "linux"
---
> More information: <https://github.com/Morganamilo/paru>.

- Interactively search for and install a package:

```bash
paru package_name_or_search_term
```

- Synchronize and update all packages:

```bash
paru
```

- Upgrade AUR packages:

```bash
paru -Sua
```

- Get information about a package:

```bash
paru -Si package_name
```

- Download `PKGBUILD` and other package source files from the AUR or ABS:

```bash
paru --getpkgbuild package_name
```

- Display the `PKGBUILD` file of a package:

```bash
paru --getpkgbuild --print package_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ishaan Bhimwal](mailto:ishaanbhimwal@protonmail.com) | linux/*: fix typos (#8227) | 2022-07-19T16:15:32 | [099ee2657117](https://github.com/tldr-pages/tldr/commit/099ee2657117da61e75d93ffae2c49690b4c8440)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Davi](mailto:davi.aug@protonmail.com) | paru: replace -P example by 2 --getpkgbuild examples (#5417) | 2021-03-13T17:02:47 | [856d526a8747](https://github.com/tldr-pages/tldr/commit/856d526a87470582faa0f41c1c6bf6fd59d426ad)
[Ben Lönnqvist](mailto:lonnqvistben@gmail.com) | paru: add page (#4894) | 2020-11-01T14:42:13 | [0db6045edf11](https://github.com/tldr-pages/tldr/commit/0db6045edf1104bd796f85e565de82cd7b7b32ef)

