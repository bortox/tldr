---
author: ['NL Sum', 'marchersimon']
date: 1633464614
title: "cmd"
description: "cmd, Windowsコマンドインタープリター。"
categories: "windows"
---
> 詳しくはこちら: <https://docs.microsoft.com/windows-server/administration/windows-commands/cmd>

- コマンドインタープリターの新しいインスタンスを開始します:

```bash
cmd
```

- 指定されたコマンドを実行して終了します:

```bash
cmd /c "コマンド"
```

- 指定されたコマンドを実行して、インタラクティブシェルに入ります:

```bash
cmd /k "コマンド"
```

- コマンドの出力での「echo」の使用を無効にします:

```bash
cmd /q
```

- コマンド拡張機能を有効または無効にします:

```bash
cmd /e:on|off
```

- ファイルまたはディレクトリのオートコンプリートを有効または無効にします:

```bash
cmd /f:on|off
```

- 環境変数の拡張を有効または無効にします:

```bash
cmd /v:on|off
```

- 出力でUnicodeエンコーディングを使用するように強制します:

```bash
cmd /u
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[NL Sum](mailto:nlsum1@users.noreply.github.com) | cmd, mkdir, mklink, find, dir, clip: add Japanese translation (#4580) | 2020-10-10T01:51:36 | [07417ed646ea](https://github.com/tldr-pages/tldr/commit/07417ed646ea1e15c240e02ef226b80e2bc89376)

