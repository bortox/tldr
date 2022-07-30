---
author: ['あでり', 'marchersimon']
date: 1633464614
title: "cp"
description: "cp, ファイルやディレクトリをコピーします。"
categories: "common"
---
> 詳しくはこちら: <https://www.gnu.org/software/coreutils/cp>

- ファイルを別の場所にコピー:

```bash
cp コピー元ファイルへのパス コピー先ファイルへのパス
```

- ファイル名を維持したまま、ファイルを別のディレクトリにコピーする:

```bash
cp コピー元ファイルへのパス コピー先ディレクトリへのパス
```

- ディレクトリの内容を別の場所に再帰的にコピーする（コピー先が存在する場合は、その中にディレクトリがコピーされる):

```bash
cp -R コピー元ディレクトリへのパス コピー先ディレクトリへのパス
```

- 詳細モードでディレクトリを再帰的にコピーする（コピーされたファイルが表示される）:

```bash
cp -vR コピー元ディレクトリへのパス コピー先ディレクトリへのパス
```

- 対話形式でテキストファイルを別の場所にコピーする（上書きする前にユーザーに確認する）:

```bash
cp -i *.txt コピー先ディレクトリへのパス
```

- コピーする前にシンボリックリンクをたどる:

```bash
cp -L link コピー先ディレクトリへのパス
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[あでり](mailto:61904065+shu-pf@users.noreply.github.com) | cp: add Japanese translation (#5907) | 2021-05-07T13:23:53 | [49939b7cad2e](https://github.com/tldr-pages/tldr/commit/49939b7cad2e490717fe877a0e950efc2278c425)

