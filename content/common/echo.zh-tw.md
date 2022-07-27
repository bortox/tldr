---
author: ['fanfly', 'Guido Lena Cota', 'Dario Vladović', 'marchersimon']
date: 1630394029
title: "echo, TLDR Pages"
description: "echo, 印出文字。"
categories: "common"
---
> 更多資訊：<https://www.gnu.org/software/coreutils/echo>.

- 印出一行文字（如果文字中沒有連續的空格，可以不加引號）：

```bash
echo "文字"
```

- 印出包含環境變數的文字：

```bash
echo "我的家目錄位於 $HOME"
```

- 印出文字，但結尾不換行：

```bash
echo -n "文字"
```

- 將一段文字加到檔案的結尾：

```bash
echo "文字" >> 檔案
```

- 將以「\\」開頭的跳脫序列轉換為特殊字元（例如「\t」會被顯示為水平定位字元）：

```bash
echo -e "第一欄\t第二欄"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo: add link (#5606) | 2021-03-30T15:54:21 | [206703144d57](https://github.com/tldr-pages/tldr/commit/206703144d576491dbcf66be20770c47ebe329d3)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[fanfly](mailto:eddie40709@gmail.com) | echo: add Traditional Chinese translation | 2020-07-21T22:51:05 | [04ebb771966f](https://github.com/tldr-pages/tldr/commit/04ebb771966f5226dcf689f7cffdc9ce9ce2eb9c)

