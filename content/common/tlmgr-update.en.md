---
author: ['marchersimon']
date: 1632484281
title: "tlmgr update, TLDR Pages"
description: "tlmgr update, Update TeX Live packages."
categories: "common"
---
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Update all TeX Live packages:

```bash
sudo tlmgr update --all
```

- Update tlmgr itself:

```bash
sudo tlmgr update --self
```

- Update a specific package:

```bash
sudo tlmgr update package
```

- Update all except a specific package:

```bash
sudo tlmgr update --all --exclude package
```

- Update all packages, making a backup of the current packages:

```bash
sudo tlmgr update --all --backup
```

- Update a specific package without updating its dependencies:

```bash
sudo tlmgr update --no-depends package
```

- Simulate updating all packages without making any changes:

```bash
sudo tlmgr update --all --dry-run
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-update: add page (#6587) | 2021-09-24T13:51:21 | [a98d06538848](https://github.com/tldr-pages/tldr/commit/a98d06538848f63b3a6041d04163df0da31f40aa)

