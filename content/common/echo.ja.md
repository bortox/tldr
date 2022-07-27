---
author: ['あでり', 'marchersimon']
date: 1633464614
title: "echo, TLDR Pages"
description: "echo, 与えられた引数を表示します。"
categories: "common"
---
> 詳しくはこちら: <https://www.gnu.org/software/coreutils/echo>

- テキストメッセージを印刷する。備考: 引用符は任意:

```bash
echo "Hello World"
```

- 環境変数のメッセージを表示する:

```bash
echo "パスは $PATH です。"
```

- メッセージを最後の改行なしで表示する:

```bash
echo -n "Hello World"
```

- ファイルにメッセージを追加する:

```bash
echo "Hello World" >> ファイル.txt
```

- バックスラッシュエスケープ（特殊文字）の解釈を可能にする:

```bash
echo -e "カラム 1\tカラム 2"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[あでり](mailto:61904065+shu-pf@users.noreply.github.com) | sed, dig, ps, echo, less, mysql, vim: add Japanese translation (#5916) | 2021-05-11T12:47:50 | [956110581b81](https://github.com/tldr-pages/tldr/commit/956110581b81e8b5813fc05fb72ddc1507b0f94d)

