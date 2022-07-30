---
author: ['marchersimon']
date: 1630819086
title: "tlmgr"
description: "tlmgr, Manages packages and configuration options of an existing TeX Live installation."
categories: "common"
---
> Some subcommands such as `tlmgr paper` have their own usage documentation.

> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Install a package and its dependencies:

```bash
tlmgr install package
```

- Remove a package and its dependencies:

```bash
tlmgr remove package
```

- Display information about a package:

```bash
tlmgr info package
```

- Update all packages:

```bash
tlmgr update --all
```

- Show possible updates without updating anything:

```bash
tlmgr update --list
```

- Start a GUI version of tlmgr:

```bash
tlmgr gui
```

- List all TeX Live configurations:

```bash
tlmgr conf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-paper: add page (#6463) | 2021-09-05T07:18:06 | [06861b8aa908](https://github.com/tldr-pages/tldr/commit/06861b8aa90800d34820d585c68bae23d8fe471a)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | latex, pdftex, tex, texdoc, texliveonfly, tlmgr: add page (#5294) | 2021-02-28T14:33:40 | [0589644d0162](https://github.com/tldr-pages/tldr/commit/0589644d0162bec7390a9ad3b417effa0577bf7b)

