---
author: ['あでり', 'lincc', 'marchersimon']
date: 1633464614
title: "vim, TLDR Pages"
description: "vim, コマンドラインのテキストエディタである Vim（Vi IMproved）には、さまざまな種類のテキスト操作のためのモードが用意されています。"
categories: "common"
---
> `i` を押すと編集モードになります。`<Esc>` を押すと通常モードに戻り、通常のテキスト挿入はできません。

> 詳しくはこちら: <https://www.vim.org>

- ファイルを開く:

```bash
vim ファイルへのパス
```

- 指定した行番号でファイルを開く:

```bash
vim +ライン番号 ファイルへのパス
```

- Vim のヘルプマニュアルを見る:

```bash
:help<Enter>
```

- 保存と終了:

```bash
:wq<Enter>
```

- 最後の操作を元に戻す:

```bash
u
```

- ファイル内のパターンを検索する（`n`/`N` を押すと次/前のマッチに進む）:

```bash
/検索パターン<Enter>
```

- ファイル全体での正規表現による置換の実行:

```bash
:%s/パターン/置き換え後/g<Enter>
```

- ライン番号の表示:

```bash
:set nu<Enter>
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | vim: refresh (#6375) | 2021-08-17T20:11:25 | [4ba58f514ad8](https://github.com/tldr-pages/tldr/commit/4ba58f514ad8d22c477708ccc673453bf583a0cb)
[あでり](mailto:61904065+shu-pf@users.noreply.github.com) | sed, dig, ps, echo, less, mysql, vim: add Japanese translation (#5916) | 2021-05-11T12:47:50 | [956110581b81](https://github.com/tldr-pages/tldr/commit/956110581b81e8b5813fc05fb72ddc1507b0f94d)

