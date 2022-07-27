---
author: ['Poy Chang']
date: 1635402678
title: "find, TLDR Pages"
description: "find, 在一個或多個文件中查詢指定字串。"
categories: "windows"
---
> 更多資訊：<https://docs.microsoft.com/windows-server/administration/windows-commands/find>.

- 查詢包含指定字串的行：

```bash
find 字串 檔案或目錄/完整/路徑
```

- 查詢不包含指定字串的行：

```bash
find 字串 檔案或目錄/完整/路徑 /v
```

- 顯示包含指定字串的行總數：

```bash
find 字串 檔案或目錄/完整/路徑 /c
```

- 顯示符合的行號：

```bash
find 字串 檔案或目錄/完整/路徑 /n
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Poy Chang](mailto:poypost@gmail.com) | cls, find: add traditional Chinese translation (#7244) | 2021-10-28T08:31:18 | [57e2f62851bc](https://github.com/tldr-pages/tldr/commit/57e2f62851bc7c14fbeef7a2fed2ef75f1885ae8)

