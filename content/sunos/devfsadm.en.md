---
author: ['Peter Tripp', 'marchersimon']
date: 1617188954
title: "devfsadm, TLDR Pages"
description: "devfsadm, Administration command for `/dev`. Maintains the `/dev` namespace."
categories: "sunos"
---
> More information: <https://www.unix.com/man-page/sunos/1m/devfsadm>.

- Scan for new disks:

```bash
devfsadm -c disk
```

- Cleanup any dangling /dev links and scan for new device:

```bash
devfsadm -C -v
```

- Dry-run - output what would be changed but make no modifications:

```bash
devfsadm -C -v -n
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sunos/*: add more information link (#5649) | 2021-03-31T13:09:14 | [d12aac42e8d5](https://github.com/tldr-pages/tldr/commit/d12aac42e8d5a4f35d0766c0cd5127ab76b6dc76)
[Peter Tripp](mailto:petertripp@gmail.com) | Add devfsadm for solaris. | 2016-01-16T19:40:51 | [0a464dfb4335](https://github.com/tldr-pages/tldr/commit/0a464dfb43356195669a0163605ad14ee42ee9a7)

