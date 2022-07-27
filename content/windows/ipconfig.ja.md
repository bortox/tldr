---
author: ['marchersimon', 'NL Sum']
date: 1633464614
title: "ipconfig, TLDR Pages"
description: "ipconfig, Windowsのネットワーク構成を表示および管理します。"
categories: "windows"
---
> 詳しくはこちら: <https://docs.microsoft.com/windows-server/administration/windows-commands/ipconfig>

- ネットワークアダプタのリストを表示します:

```bash
ipconfig
```

- ネットワークアダプタの詳細なリストを表示します:

```bash
ipconfig /all
```

- ネットワークアダプタのIPアドレスを更新します:

```bash
ipconfig /renew adapter
```

- ネットワークアダプタのIPアドレスを解放します:

```bash
ipconfig /release adapter
```

- DNSキャッシュからすべてのデータを削除します:

```bash
ipconfig /flushdns
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix period in Japanese translation (#6812) | 2021-10-05T22:10:14 | [1a98d09a48cc](https://github.com/tldr-pages/tldr/commit/1a98d09a48ccebe878f44c0afe6f0f89e1ac3518)
[NL Sum](mailto:nlsum1@users.noreply.github.com) | ipconfig: add Japanese translation (#4556) | 2020-10-07T22:43:18 | [fe394d950cc1](https://github.com/tldr-pages/tldr/commit/fe394d950cc17d8e538fecf0d5d9972df845fe91)

