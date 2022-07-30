---
author: ['Owen Voke', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1600794415
title: "comp"
description: "comp, Compare the contents of two files or sets of files."
categories: "windows"
---
> Use wildcards (*) to compare sets of files.

> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/comp>.

- Compare files interactively:

```bash
comp
```

- Compare two specified files:

```bash
comp path/to/file_1 path/to/file_2
```

- Compare two sets of files:

```bash
comp path/to/directory_1/* path/to/directory_2/*
```

- Display differences in decimal format:

```bash
comp /d path/to/file_1 path/to/file_2
```

- Display differences in ASCII format:

```bash
comp /a path/to/file_1 path/to/file_2
```

- Display line numbers for differences:

```bash
comp /l path/to/file_1 path/to/file_2
```

- Compare files case-insensitively:

```bash
comp /c path/to/file_1 path/to/file_2
```

- Compare only the first 5 lines of each file:

```bash
comp /n=5 path/to/file_1 path/to/file_2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | comp: update case-insensitive description | 2018-11-22T05:22:47 | [ceff1fda4c1e](https://github.com/tldr-pages/tldr/commit/ceff1fda4c1edad46924669922fe19477ea60cb3)
[pxgamer](mailto:owzie123@gmail.com) | comp: add wildcard sets as an example | 2018-11-22T05:22:47 | [9da6c44d672e](https://github.com/tldr-pages/tldr/commit/9da6c44d672ec90bce0fcc32ae2e57822792c582)
[pxgamer](mailto:owzie123@gmail.com) | comp: add page | 2018-11-22T05:22:47 | [01e8dad97567](https://github.com/tldr-pages/tldr/commit/01e8dad9756775affc23e521d42b3c891d956f93)

