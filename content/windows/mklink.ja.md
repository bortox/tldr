---
author: ['marchersimon', 'NL Sum']
date: 1633464614
title: "mklink, TLDR Pages"
description: "mklink, シンボリックリンクを作成します。"
categories: "windows"
---
> 詳しくはこちら: <https://docs.microsoft.com/windows-server/administration/windows-commands/mklink>

- ファイルへのシンボリックリンクを作成します:

```bash
mklink リンクパス ソースファイルのパス
```

- ディレクトリへのシンボリックリンクを作成します:

```bash
mklink /d リンクパス ソースディレクトリパス
```

- ファイルへのハードリンクを作成します:

```bash
mklink /h リンクパス ソースファイルのパス
```

- ディレクトリジャンクションを作成します:

```bash
mklink /j リンクパス ソースファイルのパス
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[NL Sum](mailto:nlsum1@users.noreply.github.com) | cmd, mkdir, mklink, find, dir, clip: add Japanese translation (#4580) | 2020-10-10T01:51:36 | [07417ed646ea](https://github.com/tldr-pages/tldr/commit/07417ed646ea1e15c240e02ef226b80e2bc89376)

