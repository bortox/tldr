---
author: ['marchersimon']
date: 1633626044
title: "tlmgr remove"
description: "tlmgr remove, Uninstall TeX Live packages."
categories: "common"
---
> By default, removed packages will be backed up to `./tlpkg/backups` under the TL installation directory.

> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Uninstall a TeX Live package:

```bash
sudo tlmgr remove package
```

- Simulate uninstalling a package without making any changes:

```bash
tlmgr remove --dry-run package
```

- Uninstall a package without its dependencies:

```bash
sudo tlmgr remove --no-depends package
```

- Uninstall a package and back it up to a specific directory:

```bash
sudo tlmgr remove --backupdir path/to/directory package
```

- Uninstall all of TeX Live, asking for confirmation:

```bash
sudo tlmgr remove --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-remove: add page (#6560) | 2021-10-07T19:00:44 | [4340c9a64ba1](https://github.com/tldr-pages/tldr/commit/4340c9a64ba1e34ad0f2e51b39194b39a9b7feaf)

