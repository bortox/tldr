---
author: ['marchersimon', 'NL Sum']
date: 1633464614
title: "find, TLDR Pages"
description: "find, 1つ以上のファイルで指定された文字列を検索します。"
categories: "windows"
---
> 詳しくはこちら: <https://docs.microsoft.com/windows-server/administration/windows-commands/find>

- 指定された文字列を含む行を検索します:

```bash
find 文字列 ファイルまたはディレクトリのパス
```

- 指定された文字列を含まない行を表示します:

```bash
find 文字列 ファイルまたはディレクトリのパス /v
```

- 指定された文字列を含む行数を表示します:

```bash
find 文字列 ファイルまたはディレクトリのパス /c
```

- 行リストとともに行番号を表示します:

```bash
find 文字列 ファイルまたはディレクトリのパス /n
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[NL Sum](mailto:nlsum1@users.noreply.github.com) | cmd, mkdir, mklink, find, dir, clip: add Japanese translation (#4580) | 2020-10-10T01:51:36 | [07417ed646ea](https://github.com/tldr-pages/tldr/commit/07417ed646ea1e15c240e02ef226b80e2bc89376)

