---
author: ['marchersimon', 'NL Sum']
date: 1633464614
title: "clip, TLDR Pages"
description: "clip, 入力コンテンツをWindowsクリップボードにコピーします。"
categories: "windows"
---
> 詳しくはこちら: <https://docs.microsoft.com/windows-server/administration/windows-commands/clip>

- コマンドライン出力をWindowsクリップボードにパイプします:

```bash
dir | clip
```

- ファイルの内容をWindowsクリップボードにコピーします:

```bash
clip < path/to/file.ext
```

- 末尾に改行が付いたテキストをWindowsクリップボードにコピーします:

```bash
echo テキスト | clip
```

- 末尾の改行なしでテキストをWindowsクリップボードにコピーします:

```bash
echo | set /p="テキスト" | clip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[NL Sum](mailto:nlsum1@users.noreply.github.com) | cmd, mkdir, mklink, find, dir, clip: add Japanese translation (#4580) | 2020-10-10T01:51:36 | [07417ed646ea](https://github.com/tldr-pages/tldr/commit/07417ed646ea1e15c240e02ef226b80e2bc89376)

