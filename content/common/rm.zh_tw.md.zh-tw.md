---
author: ['Zhe-An Li', 'Dario Vladović', 'marchersimon', 'fanfly']
date: 1630394029
title: "rm, TLDR Pages"
description: "rm, 移除檔案或目錄。"
categories: "common"
---
> 更多資訊：<https://www.gnu.org/software/coreutils/rm>.

- 移除位於指定路徑的檔案：

```bash
rm 檔案一/完整/路徑 檔案二/完整/路徑
```

- 遞迴移除目錄與其所有子目錄：

```bash
rm -r 目錄/完整/路徑
```

- 強制移除目錄，且不會跳出任何確認資訊與錯誤訊息：

```bash
rm -rf 目錄/完整/路徑
```

- 移除檔案，且每次移除都會進行確認：

```bash
rm -i 檔案一 檔案二
```

- 移除目錄中的所有檔案，並顯示每個檔案的移除資訊：

```bash
rm -v 目錄/完整/路徑/*
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | rm: add link (#5552) | 2021-03-30T09:16:08 | [62668322a827](https://github.com/tldr-pages/tldr/commit/62668322a8278797489c72f005849770fe3f51fb)
[Zhe-An Li](mailto:eddie40709@gmail.com) | mkdir, rmdir, touch, rm: fix typo (zh_TW) (#4206) | 2020-07-21T22:38:48 | [78f157e84d17](https://github.com/tldr-pages/tldr/commit/78f157e84d17cf7c82243dd01907491445f3ad02)
[fanfly](mailto:eddie40709@gmail.com) | rm: add Traditional Chinese translation | 2020-07-17T18:48:19 | [5a3416514252](https://github.com/tldr-pages/tldr/commit/5a341651425212edbf6a14056b5385fb591e8a66)

