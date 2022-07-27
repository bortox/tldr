---
author: ['marchersimon', 'NL Sum']
date: 1633464614
title: "attrib, TLDR Pages"
description: "attrib, ファイルまたはディレクトリの属性を表示または変更します。"
categories: "windows"
---
> 詳しくはこちら: <https://docs.microsoft.com/windows-server/administration/windows-commands/attrib>

- 現在のディレクトリ内のファイルの属性を表示します:

```bash
attrib
```

- 現在のディレクトリとサブディレクトリにあるファイルの属性を表示します:

```bash
attrib /S
```

- 現在のディレクトリとサブディレクトリ内のファイルとディレクトリの属性を表示します:

```bash
attrib /S /D
```

- ファイルに読み取り専用属性を追加します:

```bash
attrib +R ファイル名.txt
```

- システムとファイルの非表示属性を削除します:

```bash
attrib -S -H ファイル名.txt
```

- 非表示の属性をディレクトリに追加します:

```bash
attrib +H ディレクトリパス
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[NL Sum](mailto:nlsum1@users.noreply.github.com) | assoc, attrib, cd, choco-apikey, choco-feature, choco-info, choco, cls: add Japanese translation (#4607) | 2020-10-13T00:12:57 | [91df90534690](https://github.com/tldr-pages/tldr/commit/91df90534690ef96a255a729c2364b7a75a8d60a)

