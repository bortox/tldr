---
author: ['fanfly', 'Zhe-An Li', 'Dario Vladović', 'marchersimon']
date: 1630394029
title: "rmdir, TLDR Pages"
description: "rmdir, 移除目錄。"
categories: "common"
---
> 更多資訊：<https://www.gnu.org/software/coreutils/rmdir>.

- 若為空目錄則移除目錄（如果目錄非空，可用 `rm -r` 移除目錄及其所包含的檔案）：

```bash
rmdir 目錄/完整/路徑
```

- 移除目錄與其所有上層目錄：

```bash
rmdir -p 目錄/完整/路徑
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | rmdir: add more information link (#5566) | 2021-03-30T12:18:51 | [e56e770ab765](https://github.com/tldr-pages/tldr/commit/e56e770ab7653792e7bb1fca2f6738d2b0a7ceae)
[Zhe-An Li](mailto:eddie40709@gmail.com) | mkdir, rmdir, touch, rm: fix typo (zh_TW) (#4206) | 2020-07-21T22:38:48 | [78f157e84d17](https://github.com/tldr-pages/tldr/commit/78f157e84d17cf7c82243dd01907491445f3ad02)
[fanfly](mailto:eddie40709@gmail.com) | rmdir: add Traditional Chinese translation | 2020-07-17T18:48:19 | [fbf688528525](https://github.com/tldr-pages/tldr/commit/fbf688528525423ea2ed7ea9c424027064b86d37)

