---
author: ['Mitch Lacy', 'Stig124', 'Rafael Fidelis', 'zlbabe', 'mrx', 'Balázs Úr']
date: 1625841955
title: "dmesg, TLDR Pages"
description: "dmesg, Write the kernel messages to standard output."
categories: "linux"
---
> More information: <https://manned.org/dmesg>.

- Show kernel messages:

```bash
dmesg
```

- Show kernel error messages:

```bash
dmesg --level err
```

- Show kernel messages and keep reading new ones, similar to `tail -f` (available in kernels 3.5.0 and newer):

```bash
dmesg -w
```

- Show how much physical memory is available on this system:

```bash
dmesg | grep -i memory
```

- Show kernel messages 1 page at a time:

```bash
dmesg | less
```

- Show kernel messages with a timestamp (available in kernels 3.5.0 and newer):

```bash
dmesg -T
```

- Show kernel messages in human-readable form (available in kernels 3.5.0 and newer):

```bash
dmesg -H
```

- Colorize output (available in kernels 3.5.0 and newer):

```bash
dmesg -L
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: change Unicode characters to ASCII (#2802) Change Unicode characters to ASCII: - non-breaking spaces (\xc2\xa0) to [...] | 2019-02-25T00:56:24 | [6956cd5348e4](https://github.com/tldr-pages/tldr/commit/6956cd5348e4f87db1586a68ab299e46f7384b63)
[mrx](mailto:mike.reider@gmail.com) | dmesg: add colourise, human-readable and timestamp examples (#2728) | 2019-01-28T11:58:49 | [4abbd9bae038](https://github.com/tldr-pages/tldr/commit/4abbd9bae038c0cfadcfe82080557665df9f9cda)
[zlbabe](mailto:31076777+zlbabe@users.noreply.github.com) | dmesg: show kernel error messages (#1919) | 2018-01-22T06:00:37 | [e3eaf922dacb](https://github.com/tldr-pages/tldr/commit/e3eaf922dacb234f6be9370b141ae600315006d1)
[Rafael Fidelis](mailto:rafa_fidelis@yahoo.com.br) | dmesg: include flag to follow messages (#1446) | 2017-09-01T20:33:13 | [afd82c631130](https://github.com/tldr-pages/tldr/commit/afd82c6311303d74ee57655469df7ec46d20cc69)
[Mitch Lacy](mailto:mrlacy@uwm.edu) | dmesg: add page (#1431) | 2017-07-24T21:02:58 | [8fcc087f4937](https://github.com/tldr-pages/tldr/commit/8fcc087f49378a6251968d4a5ea5baebcf42d4af)

