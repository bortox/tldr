---
author: ['あでり', 'lincc']
date: 1643487459
title: "ps, TLDR Pages"
description: "ps, 実行中のプロセスに関する情報。"
categories: "common"
---
> 詳しくはこちら: <https://manned.org/ps>

- 実行中のプロセスをすべてリストアップ:

```bash
ps aux
```

- 実行中のすべてのプロセスを、完全なコマンド文字列を含めて一覧表示する:

```bash
ps auxww
```

- 文字列にマッチするプロセスを検索する:

```bash
ps aux | grep 文字列
```

- 現在のユーザーのすべてのプロセスを完全なフォーマットで表示する:

```bash
ps --user $(id -u) -F
```

- カレントユーザーの全プロセスをツリー状にリストアップ:

```bash
ps --user $(id -u) f
```

- プロセスの親 pid を取得する:

```bash
ps -o ppid= -p pid
```

- プロセスをメモリ消費量でソート:

```bash
ps --sort size
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[あでり](mailto:61904065+shu-pf@users.noreply.github.com) | sed, dig, ps, echo, less, mysql, vim: add Japanese translation (#5916) | 2021-05-11T12:47:50 | [956110581b81](https://github.com/tldr-pages/tldr/commit/956110581b81e8b5813fc05fb72ddc1507b0f94d)

