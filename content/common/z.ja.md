---
author: ['Kentaro Ueda', 'marchersimon']
date: 1633464614
title: "z"
description: "z, 高頻度で利用されるディレクトリを把握し、文字列や正規表現をつかうことでスムーズに移動できるようにします。"
categories: "common"
---
> 詳しくはこちら: <https://github.com/rupa/z>

- "foo"が名前に含まれるディレクトリに移動する。

```bash
z foo
```

- "foo"と"bar"が名前に含まれるディレクトリに移動する。

```bash
z foo bar
```

- "foo"と最もマッチングするディレクトリに移動する。

```bash
z -r foo
```

- "foo"とマッチングするディレクトリの中で、最も最近アクセスしたディレクトリに移動する。

```bash
z -t foo
```

- `z`コマンドのデータベースの中で、`foo` にマッチングするディレクトリの一覧を表示する。

```bash
z -l foo
```

- 現在のディレクトリを`z`コマンドのデータベース除去する。

```bash
z -x .
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[Kentaro Ueda](mailto:kentaro.ueda.kentaro@gmail.com) | z: add Japanese translation | 2020-10-24T15:20:29 | [faf926324e8e](https://github.com/tldr-pages/tldr/commit/faf926324e8ec23d830da976e5ea3b2d0a8e42fd)

