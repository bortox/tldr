---
author: ['Rult', 'bl-ue', 'Andreas Schnebinger']
date: 1621541621
title: "pamac"
description: "pamac, A command-line utility for the GUI package manager pamac."
categories: "linux"
---
> If you can't see the AUR packages, enable it in `/etc/pamac.conf` or in the GUI.

> More information: <https://wiki.manjaro.org/index.php/Pamac>.

- Install a new package:

```bash
pamac install package_name
```

- Remove a package and its no longer required dependencies (orphans):

```bash
pamac remove --orphans package_name
```

- Search the package database for a package:

```bash
pamac search package_name
```

- List installed packages:

```bash
pamac list --installed
```

- Check for package updates:

```bash
pamac checkupdates
```

- Upgrade all packages:

```bash
pamac upgrade
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Rult](mailto:20477460+Rult@users.noreply.github.com) | pamac: add note about AUR packages in the command description (#5655) | 2021-04-01T21:53:40 | [090cdd9b3d53](https://github.com/tldr-pages/tldr/commit/090cdd9b3d534d43cb3096253883e1490226f486)
[Andreas Schnebinger](mailto:Iniesta8@users.noreply.github.com) | pamac: add page (#2573) | 2018-11-12T22:22:06 | [fb9011f6f978](https://github.com/tldr-pages/tldr/commit/fb9011f6f97848414c1142c44be62dbb355a5a7f)

