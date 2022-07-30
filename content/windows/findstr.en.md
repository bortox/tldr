---
author: ['Owen Voke', 'Lucas Gabriel Schneider', 'NNRepos']
date: 1600794415
title: "findstr"
description: "findstr, Find specified text within one or more files."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/findstr>.

- Find space-separated string(s) in all files:

```bash
findstr "query" *
```

- Find space-separated string(s) in a piped command's output:

```bash
dir | findstr "query"
```

- Find space-separated string(s) in all files recur[s]ively:

```bash
findstr /s "query" *
```

- Find strings using a case-insensitive search:

```bash
findstr /i "query" *"
```

- Find strings in all files using regular expressions:

```bash
findstr /r "expression" *
```

- Find a literal string (containing spaces) in all text files:

```bash
findstr /c:"query" *.txt
```

- Display the line number before each matching line:

```bash
findstr /n "query" *
```

- Display only the filenames that contain a match:

```bash
findstr /m "query" *
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[NNRepos](mailto:45516943+NNRepos@users.noreply.github.com) | findstr: edit-page (#3509) | 2019-11-09T14:37:46 | [aa5032017027](https://github.com/tldr-pages/tldr/commit/aa5032017027e585c5f41eeabda4a4d01e4989f1)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | findstr: add page (#2336) | 2018-09-16T21:32:14 | [5133b73a6aa0](https://github.com/tldr-pages/tldr/commit/5133b73a6aa07ffe357872c336d5d2c7ec090efe)

