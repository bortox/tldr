---
author: ['あでり', 'marchersimon']
date: 1633464614
title: "ls, TLDR Pages"
description: "ls, ディレクトリの内容を一覧表示します。"
categories: "common"
---
> 詳しくはこちら: <https://www.gnu.org/software/coreutils/ls>

- ファイルを1行ごとに一覧表示:

```bash
ls -1
```

- 隠しファイルを含むすべてのファイルを一覧表示:

```bash
ls -a
```

- すべてのファイルを一覧表示し、ディレクトリ名の最後に `/` を付加する:

```bash
ls -F
```

- 全ファイルを長い形式（パーミッション、所有者、サイズ、修正日）で一覧表示します:

```bash
ls -la
```

- サイズを人間が読みやすい単位（KiB、MiB、GiB）で表示した長い形式での一覧表示:

```bash
ls -lh
```

- サイズ順（降順）に並べた長い形式での一覧表示:

```bash
ls -lS
```

- すべてのファイルの長い形式でのリストで、更新日が古いものから順に表示されます:

```bash
ls -ltr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[あでり](mailto:61904065+shu-pf@users.noreply.github.com) | ls: add Japanese translation (#5903) | 2021-05-07T14:58:41 | [fc70d7c075b0](https://github.com/tldr-pages/tldr/commit/fc70d7c075b0e4285db95644c4c7f9ee7a215e0f)

