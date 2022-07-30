---
author: ['Sanosuke Kato']
date: 1634751170
title: "alias"
description: "alias, alias （コマンド文字列を置き換える別名）を作成します。"
categories: "common"
---
> alias は `~/.bashrc` などの shell の設定ファイルで定義されない限り、現在のセッションで失効します。

> 詳しくはこちら: <https://tldp.org/LDP/abs/html/aliases.html>

- alias の一覧表示:

```bash
alias
```

- alias を作成する:

```bash
alias 別名="コマンド"
```

- 指定した alias に紐付くコマンドの表示:

```bash
alias 別名
```

- 作成された alias の削除:

```bash
unalias 別名
```

- `rm` を対話型にする:

```bash
alias rm="rm -i"
```

- `ls -a` のショートカットして `la` を作成する:

```bash
alias la="ls -a"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sanosuke Kato](mailto:8940110+sanopy@users.noreply.github.com) | alias: add Japanese translation (#7056) | 2021-10-20T19:32:50 | [c6a07d3ae2a7](https://github.com/tldr-pages/tldr/commit/c6a07d3ae2a72897695c4028603790cca7964022)

