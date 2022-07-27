---
author: ['lincc', 'marchersimon']
date: 1630394029
title: "cp, TLDR Pages"
description: "cp, 複製檔案或整個目錄。"
categories: "common"
---
> 更多資訊：<https://www.gnu.org/software/coreutils/cp>.

- 將檔案複製到另一個位置：

```bash
cp 檔案一/完整/路徑 檔案二/完整/路徑
```

- 將檔案複製到另一個目錄下，並保留原本的檔名：

```bash
cp 檔案/完整/路徑 目錄/完整/路徑
```

- 以遞迴方式將目錄一的內容複製到目錄二（如果目錄二存在，則目錄一複製為目錄二的子目錄）：

```bash
cp -R 目錄一/完整/路徑 目錄二/完整/路徑
```

- 以詳細模式遞迴複製目錄（複製時逐一顯示檔案信息）：

```bash
cp -vR 目錄一/完整/路徑 目錄二/完整/路徑
```

- 以互動模式將 txt 檔複製到另一個目錄下（在覆寫之前提示使用者）：

```bash
cp -i *.txt 目錄/完整/路徑
```

- 複製前遵循符號連結：

```bash
cp -L 符號連結 目錄/完整/路徑
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | cp: add traditional Chinese translation (#6201) | 2021-07-07T14:10:37 | [97c58c39c675](https://github.com/tldr-pages/tldr/commit/97c58c39c675b65500603f812369493858471133)

