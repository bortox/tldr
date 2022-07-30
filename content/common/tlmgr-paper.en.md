---
author: ['a1346054', 'marchersimon']
date: 1631763133
title: "tlmgr paper"
description: "tlmgr paper, Manage paper size options of an TeX Live installation."
categories: "common"
---
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Show the default paper size used by all TeX Live programs:

```bash
tlmgr paper
```

- Set the default paper size for all TeX Live programs to A4:

```bash
sudo tlmgr paper a4
```

- Show the default paper size used by a specific TeX Live program:

```bash
tlmgr pdftex paper
```

- Set the default paper size for a specific TeX Live program to A4:

```bash
sudo tlmgr pdftex paper a4
```

- List all available paper sizes for a specific TeX Live program:

```bash
tlmgr pdftex paper --list
```

- Dump the default paper size used by all TeX Live programs in JSON format:

```bash
tlmgr paper --json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[a1346054](mailto:36859588+a1346054@users.noreply.github.com) | *: shellcheck and fix typos (#6526) * test.sh: quote a variable * contributing-guides/*: fix typos * pages/*: fix typos * scripts/*: [...] | 2021-09-16T05:32:13 | [5c62e303b5ab](https://github.com/tldr-pages/tldr/commit/5c62e303b5ab7c0f38b360c3918380ccd011a536)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-paper: add page (#6463) | 2021-09-05T07:18:06 | [06861b8aa908](https://github.com/tldr-pages/tldr/commit/06861b8aa90800d34820d585c68bae23d8fe471a)

