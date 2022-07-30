---
author: ['Axel Navarro', 'Dario Vladović', 'fanfly', 'marchersimon']
date: 1630394029
title: "ls"
description: "ls, 列出目錄內容。"
categories: "common"
---
> 更多資訊：<https://www.gnu.org/software/coreutils/ls>.

- 列出目錄中的檔案，其中每個檔案佔一行：

```bash
ls -1
```

- 列出包含隱藏檔案的所有檔案：

```bash
ls -a
```

- 列出檔案，並依照檔案類型在檔案後面加上對應的符號（例如目錄會加上「/」）：

```bash
ls -F
```

- 列出包含隱藏檔案的完整檔案列表（包括權限、擁有者、檔案大小與修改日期）：

```bash
ls -la
```

- 列出完整檔案列表，其中檔案大小會用 KiB、MiB、GiB 表示：

```bash
ls -lh
```

- 列出完整檔案列表，並依檔案大小降序排序：

```bash
ls -lS
```

- 列出完整檔案列表，並依修改時間由舊到新排序：

```bash
ls -ltr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ls: add link (#5561) | 2021-03-30T09:12:42 | [a0e1beab9bd7](https://github.com/tldr-pages/tldr/commit/a0e1beab9bd704de488fefaca86d0c5e20a7a03b)
[Axel Navarro](mailto:navarroaxel@gmail.com) | ls: fix size units in example description (#5451) | 2021-03-15T20:57:50 | [8402bf0fa60e](https://github.com/tldr-pages/tldr/commit/8402bf0fa60e2e1d94b94c75aeceba8ed40fc409)
[fanfly](mailto:eddie40709@gmail.com) | ls: add Traditional Chinese translation | 2020-07-17T18:48:19 | [f220cf46ae00](https://github.com/tldr-pages/tldr/commit/f220cf46ae0016194eb81c28b4aaa17700d794ca)

