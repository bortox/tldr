---
author: ['lbonanomi', 'Emily Grace Seville']
date: 1647882468
title: "utmpdump, TLDR Pages"
description: "utmpdump, Dump and load btmp, utmp and wtmp accounting files."
categories: "linux"
---
> More information: <https://manned.org/utmpdump>.

- Dump the `/var/log/wtmp` file to the standard output as plain text:

```bash
utmpdump /var/log/wtmp
```

- Load a previously dumped file into `/var/log/wtmp`:

```bash
utmpdump -r dumpfile > /var/log/wtmp
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | utmpdump: add page (#2931) | 2019-04-19T08:29:16 | [dac29ac7e02d](https://github.com/tldr-pages/tldr/commit/dac29ac7e02d5ed89ceef9d28ef4fd457c310cd5)

