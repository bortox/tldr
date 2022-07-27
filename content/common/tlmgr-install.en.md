---
author: ['marchersimon']
date: 1632239610
title: "tlmgr install, TLDR Pages"
description: "tlmgr install, Install TeX Live packages."
categories: "common"
---
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Install a package and its dependencies:

```bash
sudo tlmgr install package
```

- Reinstall a package:

```bash
sudo tlmgr install --reinstall package
```

- Simulate installing a package without making any changes:

```bash
tlmgr install --dry-run package
```

- Install a package without its dependencies:

```bash
sudo tlmgr install --no-depends package
```

- Install a package from a specific file:

```bash
sudo tlmgr install --file path/to/package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-install: add page (#6559) | 2021-09-21T17:53:30 | [27822976ef48](https://github.com/tldr-pages/tldr/commit/27822976ef48691c615138f2b2df5e8e219e35b3)

