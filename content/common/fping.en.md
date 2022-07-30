---
author: ['Waldir Pimenta', 'pxgamer', 'Max Xu']
date: 1559944739
title: "fping"
description: "fping, A more powerful ping which can ping multiple hosts."
categories: "common"
---
> More information: <https://fping.org>.

- List alive hosts within a subnet generated from a netmask:

```bash
fping -a -g 192.168.1.0/24
```

- List alive hosts within a subnet generated from an IP range:

```bash
fping -a -g 192.168.1.1 192.168.1.254
```

- List unreachable hosts within a subnet generated from a netmask:

```bash
fping -u -g 192.168.1.0/24
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | fping: add link to homepage | 2019-06-07T23:58:59 | [cc079fc09c7d](https://github.com/tldr-pages/tldr/commit/cc079fc09c7d6e0472a914fde72e64b9977661ac)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fping: a IP --> an IP | 2017-06-09T23:50:23 | [5085853d51f6](https://github.com/tldr-pages/tldr/commit/5085853d51f660e6fbb72825886e0b652dadf394)
[Max Xu](mailto:xuhuan@live.cn) | fping: add page (#1395) | 2017-06-08T12:25:51 | [4bbb5c887614](https://github.com/tldr-pages/tldr/commit/4bbb5c88761409fae48f63c4b3de24326753c36a)

