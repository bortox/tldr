---
author: ['Sanosuke Kato', 'marchersimon']
date: 1633464614
title: "test, TLDR Pages"
description: "test, 条件を評価します。"
categories: "common"
---
> 条件が真と評価された場合は 0 を、偽と評価された場合は 1 を返します。

> 詳しくはこちら: <https://www.gnu.org/software/coreutils/test>

- 与えられた変数が与えられた文字列と等しいかどうかをテスト:

```bash
test "$変数名" == "/bin/zsh"
```

- 与えられた変数が空であるかどうかをテスト:

```bash
test -z "$変数名"
```

- ファイルが存在するかどうかをテスト:

```bash
test -f "ファイルへのパス"
```

- ディレクトリが存在しないかどうかをテスト:

```bash
test ! -d "ディレクトリへのパス"
```

- if-else 文:

```bash
test 条件 && echo "真" || echo "偽"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[Sanosuke Kato](mailto:8940110+sanopy@users.noreply.github.com) | test: add Japanese translation (#6725) | 2021-10-04T04:26:19 | [3e9b86ae4e44](https://github.com/tldr-pages/tldr/commit/3e9b86ae4e441f00c287073e6e2b2e6c45133f37)

