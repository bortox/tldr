---
author: ['あでり', 'marchersimon']
date: 1633464614
title: "sed, TLDR Pages"
description: "sed, スクリプトによるテキスト編集。"
categories: "common"
---
> 詳しくはこちら: <https://man.archlinux.org/man/sed.1>

- ファイルの各行で正規表現の最初の出現箇所を置換し、その結果を表示する:

```bash
sed 's/正規表現/置き換え後/' ファイル名
```

- ファイル内の拡張正規表現のすべての出現箇所を置換し、その結果を表示する:

```bash
sed -r 's/正規表現/置き換え後/g' ファイル名
```

- ファイル内のすべての文字列を置き換え、ファイルを上書きする(すなわち インプレイス):

```bash
sed -i 's/置き換え前/置き換え後/g' ファイル名}
```

- ラインパターンに一致する行のみを置換:

```bash
sed '/ラインパターン/s/置き換え前/置き換え後/' ファイル名
```

- ラインパターンに一致する行を削除する:

```bash
sed '/ラインパターン/d' ファイル名}
```

- ファイルの最初の 11 行を表示する:

```bash
sed 11q ファイル名
```

- 複数の検索・置換式をファイルに適用:

```bash
sed -e 's/置き換え名/置き換え後/' -e 's/置き換え前/置き換え後/' ファイル名
```

- 区切り文字 `/` を、検索や置換のパターンで使われていない他の文字（例：`#`）で置き換える:

```bash
sed 's#置き換え前#置き換え後#' ファイル名
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[あでり](mailto:61904065+shu-pf@users.noreply.github.com) | sed, dig, ps, echo, less, mysql, vim: add Japanese translation (#5916) | 2021-05-11T12:47:50 | [956110581b81](https://github.com/tldr-pages/tldr/commit/956110581b81e8b5813fc05fb72ddc1507b0f94d)

