---
author: ['Miyuutsu', 'RyotaK', 'bl-ue', 'marchersimon']
date: 1633464614
title: "7za, TLDR Pages"
description: "7za, 圧縮率の高いファイルアーカイバです。"
categories: "common"
---
> `7z` よりも対応しているファイル形式は少ないですが、複数のプラットフォームに対応しています。

> 詳しくはこちら: <https://www.7-zip.org>

- ファイルまたはディレクトリを圧縮する:

```bash
7za a アーカイブ.7z ファイルまたはディレクトリへのパス
```

- 元のディレクトリ構造を保持したまま展開する:

```bash
7za x アーカイブ.7z
```

- 特定のアーカイブ形式を使用した圧縮を行う:

```bash
7za a -tzip|gzip|bzip2|tar アーカイブ.7z ファイルまたはディレクトリへのパス
```

- 利用可能なアーカイブ形式を出力する:

```bash
7za i
```

- アーカイブの内容を表示する:

```bash
7za l アーカイブ.7z
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[RyotaK](mailto:49341894+Ry0taK@users.noreply.github.com) | 7z, 7za, 7zr: fix Japanese translation (#6661) | 2021-10-03T15:48:52 | [6d4248f1f1fc](https://github.com/tldr-pages/tldr/commit/6d4248f1f1fcf5606a12fb1067eedba102f9a7c3)
[RyotaK](mailto:49341894+Ry0taK@users.noreply.github.com) | 7za: fix Japanese translation (#6663) | 2021-10-03T15:35:03 | [53805ce0d23e](https://github.com/tldr-pages/tldr/commit/53805ce0d23e02b187e9fd4522ea01490728d9cf)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Miyuutsu](mailto:Miyuu@miyuu.pw) | 7za: add Japanese translation (#4812) * 7za: add Japanese translation * Rename 7za to 7za.md * Update 7za.md * Update 7za.md | 2020-10-24T14:55:58 | [60a8c298b8c8](https://github.com/tldr-pages/tldr/commit/60a8c298b8c8d3717f8c2f51fd25b6122bf03562)

