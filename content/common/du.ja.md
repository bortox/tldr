---
author: ['Dario Vladović', 'Lucas Gabriel Schneider', 'ktrueda', 'marchersimon']
date: 1634848494
title: "du"
description: "du, ディスク使用状況: ファイルとディレクトリの使用量の概算を表示します。"
categories: "common"
---
> 詳しくはこちら: <https://www.gnu.org/software/coreutils/du>

- 指定した単位 (B/KiB/MiB) でディレクトリおよびサブディレクトリのサイズを表示します。

```bash
du -b|k|m path/to/directory
```

- 人間にとって解釈しやすい形式(サイズに応じた単位の選択など)で、ディレクトリおよびサブディレクトリのサイズを表示します。

```bash
du -h path/to/directory
```

- 人間にとって解釈しやすい形式で、単一ディレクトリのサイズを表示します。

```bash
du -sh path/to/directory
```

- 人間にとって解釈しやすい形式で、指定ディレクトリ、そのサブディレクトリ、それらに含まれる全てのファイルのサイズを表示します。

```bash
du -ah path/to/directory
```

- 人間にとって解釈しやすい形式で、指定ディレクトリおよび N 階層先までのディレクトリのサイズを表示します。

```bash
du -h --max-depth=N path/to/directory
```

- 人間にとって解釈しやすい形式で、現在のディレクトリおよびその下のディレクトリに含まれる全ての `.jpg` ファイルサイズを表示し、最後に合計を表示します。

```bash
du -ch */*.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | du: fix wrong byte units (#7131) | 2021-10-21T22:34:54 | [0ddea62ffb82](https://github.com/tldr-pages/tldr/commit/0ddea62ffb822afabf0437c9a0d15258f13ce672)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | du: add more information link (#5605) | 2021-03-30T15:55:04 | [5ba367c2dd90](https://github.com/tldr-pages/tldr/commit/5ba367c2dd907bb693651c017f68ce0ee42ca3f1)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[ktrueda](mailto:ktrueda@users.noreply.github.com) | du: add Japanese translation (#4581) | 2020-10-08T21:39:06 | [24d18d1af773](https://github.com/tldr-pages/tldr/commit/24d18d1af7737ac2d91951317198e72470f8db8b)

