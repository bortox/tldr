---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'Yan Uehara', 'Owen Voke']
date: 1600794415
title: "attrib, TLDR Pages"
description: "attrib, Displays or changes file and directory attributes."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/attrib>.

- Display the attributes of the files in the current directory:

```bash
attrib
```

- Display the attributes of the files in the current directory and sub-directories:

```bash
attrib /S
```

- Display the attributes of the files and directories in the current directory and sub-directories:

```bash
attrib /S /D
```

- Add the read-only attribute to a file:

```bash
attrib +R document.txt
```

- Remove the system and hidden attributes of a file:

```bash
attrib -S -H document.txt
```

- Add the hidden attribute to a directory:

```bash
attrib +H path\to\directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Yan Uehara](mailto:yanuehara@hotmail.com) | attrib: add page (#1616) | 2017-11-13T06:40:05 | [1905be409295](https://github.com/tldr-pages/tldr/commit/1905be40929597c88a34a31051d92adcf4666bf5)

