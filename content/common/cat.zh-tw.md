---
author: ['fanfly', 'Dario Vladović', 'marchersimon']
date: 1630394029
title: "cat"
description: "cat, 連接檔案並印出檔案的內容。"
categories: "common"
---
> 更多資訊：<https://www.gnu.org/software/coreutils/cat>.

- 將檔案的內容印在標準輸出：

```bash
cat 檔案
```

- 將多個檔案連接起來，輸出至目標檔案：

```bash
cat 檔案一 檔案二 > 目標檔案
```

- 將多個檔案連接起來，並將其內容加到目標檔案的結尾：

```bash
cat 檔案一 檔案二 >> 目標檔案
```

- 印出檔案的內容並顯示行號：

```bash
cat -n 檔案
```

- 印出檔案的內容，且將無法顯示的字元用特殊的方式顯示出來：

```bash
cat -v -t -e 檔案
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[fanfly](mailto:eddie40709@gmail.com) | cat: add Traditional Chinese translation | 2020-07-21T22:51:05 | [8ea907530a28](https://github.com/tldr-pages/tldr/commit/8ea907530a285422bdfdc85f5a0a33bbcd4fd992)

