---
author: ['marchersimon', 'NL Sum']
date: 1633464614
title: "choco-apikey, TLDR Pages"
description: "choco-apikey, ChocolateyソースのAPIキーを管理します。"
categories: "windows"
---
> 詳しくはこちら: <https://chocolatey.org/docs/commands-apikey>

- ソースとそのAPIキーのリストを表示します:

```bash
choco apikey
```

- 特定のソースとそのAPIキーを表示します:

```bash
choco apikey --source "ソースURL"
```

- ソースのAPIキーを設定します:

```bash
choco apikey --source "ソースURL" --key "APIキー"
```

- ソースのAPIキーを削除します:

```bash
choco apikey --source "ソースURL" --remove
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[NL Sum](mailto:nlsum1@users.noreply.github.com) | assoc, attrib, cd, choco-apikey, choco-feature, choco-info, choco, cls: add Japanese translation (#4607) | 2020-10-13T00:12:57 | [91df90534690](https://github.com/tldr-pages/tldr/commit/91df90534690ef96a255a729c2364b7a75a8d60a)

