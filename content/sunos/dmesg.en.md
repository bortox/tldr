---
author: ['Mitch Lacy', 'Balázs Úr', 'marchersimon']
date: 1617188954
title: "dmesg, TLDR Pages"
description: "dmesg, Write the kernel messages to standard output."
categories: "sunos"
---
> More information: <https://www.unix.com/man-page/sunos/1m/dmesg>.

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
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sunos/*: add more information link (#5649) | 2021-03-31T13:09:14 | [d12aac42e8d5](https://github.com/tldr-pages/tldr/commit/d12aac42e8d5a4f35d0766c0cd5127ab76b6dc76)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: change Unicode characters to ASCII (#2802) Change Unicode characters to ASCII: - non-breaking spaces (\xc2\xa0) to [...] | 2019-02-25T00:56:24 | [6956cd5348e4](https://github.com/tldr-pages/tldr/commit/6956cd5348e4f87db1586a68ab299e46f7384b63)
[Mitch Lacy](mailto:mrlacy@uwm.edu) | dmesg: add page (#1431) | 2017-07-24T21:02:58 | [8fcc087f4937](https://github.com/tldr-pages/tldr/commit/8fcc087f49378a6251968d4a5ea5baebcf42d4af)

