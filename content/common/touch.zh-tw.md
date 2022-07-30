---
author: ['fanfly', 'Zhe-An Li', 'Dario Vladović', 'marchersimon']
date: 1630394029
title: "touch"
description: "touch, 改變檔案的存取與修改時間。"
categories: "common"
---
> 更多資訊：<https://www.gnu.org/software/coreutils/touch>.

- 建立新檔案，或更新現存檔案的存取與修改時間：

```bash
touch 檔案名稱
```

- 將存取與修改時間設定為指定時刻：

```bash
touch -t 西元年份月份日期小時分鐘.秒鐘 檔案名稱
```

- 以其中一個檔案的存取與修改時間為基準，設定另一個檔案的存取與修改時間：

```bash
touch -r 來源檔案名稱 目標檔案名稱
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | touch: change link (#5550) | 2021-03-30T09:15:08 | [64814bb7bac0](https://github.com/tldr-pages/tldr/commit/64814bb7bac00f937c245a550a19dc2c4b62d14f)
[Zhe-An Li](mailto:eddie40709@gmail.com) | mkdir, rmdir, touch, rm: fix typo (zh_TW) (#4206) | 2020-07-21T22:38:48 | [78f157e84d17](https://github.com/tldr-pages/tldr/commit/78f157e84d17cf7c82243dd01907491445f3ad02)
[fanfly](mailto:eddie40709@gmail.com) | touch: add Traditional Chinese translation | 2020-07-17T18:48:19 | [fe786537e087](https://github.com/tldr-pages/tldr/commit/fe786537e08714e4faeaf0a4b6a8167a5ee8eaba)

