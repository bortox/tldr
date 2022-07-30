---
author: ['Chenfa Zheng']
date: 1648990566
title: "debtap"
description: "debtap, Convert Debian packages into Arch Linux packages."
categories: "linux"
---
> See also: `pacman-upgrade`.

> More information: <https://github.com/helixarch/debtap>.

- Update debtap database (before the first run):

```bash
sudo debtap --update
```

- Convert the specified package:

```bash
debtap path/to/package.deb
```

- Convert the specified package bypassing all questions, except for editing metadata files:

```bash
debtap --quiet path/to/package.deb
```

- Generate a PKGBUILD file:

```bash
debtap --pkgbuild path/to/package.deb
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Chenfa Zheng](mailto:80394200+ChenfaZheng@users.noreply.github.com) | debtap: add page (#7947) | 2022-04-03T14:56:06 | [48c442da5d33](https://github.com/tldr-pages/tldr/commit/48c442da5d339d71d8a2e236ea7798ade94a6661)

