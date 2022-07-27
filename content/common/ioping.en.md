---
author: ['pxgamer', 'Ruben Vereecken', 'Agno94', 'Felix Yan']
date: 1603970505
title: "ioping, TLDR Pages"
description: "ioping, Monitor I/O latency in real time."
categories: "common"
---
> More information: <https://github.com/koct9i/ioping>.

- Show disk I/O latency using the default values and the current directory:

```bash
ioping .
```

- Measure latency on /tmp using 10 requests of 1 megabyte each:

```bash
ioping -c 10 -s 1M /tmp
```

- Measure disk seek rate on `/dev/sdX`:

```bash
ioping -R /dev/sdX
```

- Measure disk sequential speed on `/dev/sdX`:

```bash
ioping -RL /dev/sdX
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Agno94](mailto:agnophi@gmail.com) | badblocks, ddrescue, fdisk, fsck, ioping, smartctl, wipefs: change /dev/sda into /dev/sdX (#4861) | 2020-10-29T12:21:45 | [c312c50b9906](https://github.com/tldr-pages/tldr/commit/c312c50b99062c4dca949685ddc31385b179b7d5)
[pxgamer](mailto:owzie123@gmail.com) | ioping: add link to homepage | 2019-06-06T04:42:48 | [0b7b454669f1](https://github.com/tldr-pages/tldr/commit/0b7b454669f1da12db62204ac3a97a95e93f1fdf)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Felix Yan](mailto:felixonmars@archlinux.org) | ioping: add page | 2015-12-28T10:36:54 | [9e2ad549a755](https://github.com/tldr-pages/tldr/commit/9e2ad549a755b06b512bb7f7966d39eee0e2a775)

