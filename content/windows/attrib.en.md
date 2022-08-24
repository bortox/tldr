---
author: ['Owen Voke', 'Emily Grace Seville', 'Yan Uehara', 'Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1661282407
title: "attrib"
description: "attrib, Display or change attributes of files or directories."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/attrib>.

- Display all set attributes of files in the current directory:

```bash
attrib
```

- Display all set attributes of files in a specific directory:

```bash
attrib path\to\directory
```

- Display all set attributes of files and [d]irectories in the current directory:

```bash
attrib /d
```

- Display all set attributes of files in the current directory and [s]ub-directories:

```bash
attrib /s
```

- Add the `[r]ead-only` or `[a]rchive` or `[s]ystem` or `[h]idden` or `not content [i]ndexed` attribute to files or directories:

```bash
attrib +r|a|s|h|i path\to\file_or_directory1 path\to\file_or_directory2 ...
```

- Remove a specific attribute of files or directories:

```bash
attrib -r|a|s|h|i path\to\file_or_directory1 path\to\file_or_directory2 ...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | assoc, attrib: update page (#8349) | 2022-08-23T21:20:07 | [38d904a40872](https://github.com/tldr-pages/tldr/commit/38d904a4087259d1020050358f0210f737a0ff51)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Yan Uehara](mailto:yanuehara@hotmail.com) | attrib: add page (#1616) | 2017-11-13T06:40:05 | [1905be409295](https://github.com/tldr-pages/tldr/commit/1905be40929597c88a34a31051d92adcf4666bf5)

