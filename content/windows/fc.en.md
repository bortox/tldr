---
author: ['Owen Voke', 'Lucas Gabriel Schneider']
date: 1600794415
title: "fc"
description: "fc, Compare the differences between two files or sets of files."
categories: "windows"
---
> Use wildcards (*) to compare sets of files.

> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/fc>.

- Compare 2 specified files:

```bash
fc path/to/file_1 path/to/file_2
```

- Perform a case-insensitive comparison:

```bash
fc /c path/to/file_1 path/to/file_2
```

- Compare files as Unicode text:

```bash
fc /u path/to/file_1 path/to/file_2
```

- Compare files as ASCII text:

```bash
fc /l path/to/file_1 path/to/file_2
```

- Compare files as binary:

```bash
fc /b path/to/file_1 path/to/file_2
```

- Disable tab-to-space expansion:

```bash
fc /t path/to/file_1 path/to/file_2
```

- Compress whitespace (tabs and spaces) for comparisons:

```bash
fc /w path/to/file_1 path/to/file_2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | fc: add page (#2655) | 2019-01-28T19:38:53 | [548465e275e2](https://github.com/tldr-pages/tldr/commit/548465e275e23963112fd53b78b962292faf7935)

