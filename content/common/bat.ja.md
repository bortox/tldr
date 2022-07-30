---
author: ['uh-zz']
date: 1635361100
title: "bat"
description: "bat, ファイルの内容を表示したり、連結したりします。"
categories: "common"
---
> シンタックスハイライトと Git 統合を備えた `cat`クローンです。

> 詳しくはこちら: <https://github.com/sharkdp/bat>

- ファイルの内容を、標準出力に出力する:

```bash
bat ファイル
```

- 複数のファイルの内容を連結して、目的のファイルに書き込む:

```bash
bat ファイル1 ファイル2 > ターゲットファイル}
```

- 複数のファイルの内容を連結して、目的のファイルに追記する:

```bash
bat ファイル1 ファイル2 >> ターゲットファイル
```

- すべての出力行に番号をつける:

```bash
bat -n ファイル
```

- JSON ファイルをハイライトする構文:

```bash
bat --language json JSONファイル
```

- すべての対応言語を表示する:

```bash
bat --list-languages
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[uh-zz](mailto:uhzz.contact@gmail.com) | asdf, bat: fixed placeholder to Japanese | 2021-10-27T20:58:20 | [eb0a1aebd431](https://github.com/tldr-pages/tldr/commit/eb0a1aebd4315eb8245007a446f4b46a988d977d)
[uh-zz](mailto:uhzz.contact@gmail.com) | bat: add Japanese translation | 2021-10-27T20:58:20 | [9cb56ad3480e](https://github.com/tldr-pages/tldr/commit/9cb56ad3480e7147671e14ed7cdc73dda313523b)

