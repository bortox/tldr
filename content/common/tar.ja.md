---
author: ['あでり', 'marchersimon']
date: 1633464614
title: "tar, TLDR Pages"
description: "tar, アーカイブ(複数のファイルやフォルダを 1 つのファイルに纏める)の為のユーティリティー。"
categories: "common"
---
> gzip や bzip2 などの圧縮方法と組み合わせることが多いです。

> 詳しくはこちら: <https://www.gnu.org/software/tar>

- アーカイブを作成し、それをファイルに書き込む:

```bash
tar cf 出力ファイル名.tar ファイル1 ファイル2 ファイル3
```

- gzip 形式で圧縮されたアーカイブを作成し、それをファイルに書き込む:

```bash
tar czf 出力ファイル名.tar.gz ファイル1 ファイル2 ファイル3
```

- 相対パスを用いてディレクトリから gzip 形式のアーカイブを作成する:

```bash
tar czf 出力ファイル名.tar.gz --directory=ディレクトリへの相対パス .
```

- (圧縮された)アーカイブファイルを、カレントディレクトリに過程を詳細表示しながら展開する:

```bash
tar xvf 入力ファイル名.tar[.gz|.bz2|.xz]
```

- (圧縮された)アーカイブファイルを、指定のディレクトリに展開する:

```bash
tar xf 入力ファイル名.tar[.gz|.bz2|.xz] --directory=ディレクトリ
```

- 圧縮されたアーカイブを作成し、それにファイルを書き込む。なお、接尾辞で圧縮プログラムを指定する:

```bash
tar caf 出力ファイル名.tar.xz ファイル1 ファイル2 ファイル3
```

- tar ファイルの内容を詳細に表示する:

```bash
tar tvf 入力ファイル名.tar
```

- アーカイブファイルからパターンに合致するファイルを抽出する:

```bash
tar xf 入力ファイル名.tar --wildcards "*.html"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[あでり](mailto:61904065+shu-pf@users.noreply.github.com) | tar: add Japanese translation (#5905) | 2021-05-07T14:15:11 | [6a64d2aad185](https://github.com/tldr-pages/tldr/commit/6a64d2aad1859c1120506e0cb68ef0107cc6d515)

