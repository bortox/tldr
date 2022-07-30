---
author: ['Balázs Úr', 'Mitch Lacy', 'Emily Grace Seville']
date: 1644837703
title: "dmesg"
description: "dmesg, Write the kernel messages to standard output."
categories: "osx"
---
> More information: <https://www.manpagez.com/man/8/dmesg/>.

- Show kernel messages:

```bash
dmesg
```

- Show how much physical memory is available on this system:

```bash
dmesg | grep -i memory
```

- Show kernel messages 1 page at a time:

```bash
dmesg | less
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: change Unicode characters to ASCII (#2802) Change Unicode characters to ASCII: - non-breaking spaces (\xc2\xa0) to [...] | 2019-02-25T00:56:24 | [6956cd5348e4](https://github.com/tldr-pages/tldr/commit/6956cd5348e4f87db1586a68ab299e46f7384b63)
[Mitch Lacy](mailto:mrlacy@uwm.edu) | dmesg: add page (#1431) | 2017-07-24T21:02:58 | [8fcc087f4937](https://github.com/tldr-pages/tldr/commit/8fcc087f49378a6251968d4a5ea5baebcf42d4af)

