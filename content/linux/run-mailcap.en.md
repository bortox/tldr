---
author: ['Igor Shubovych', 'Balázs Úr', 'Emily Grace Seville']
date: 1647882468
title: "run-mailcap, TLDR Pages"
description: "run-mailcap, Run MailCap Programs."
categories: "linux"
---
> Run mailcap view, see, edit, compose, print - execute programs via entries in the mailcap file (or any of its aliases) will use the given action to process each mime-type/file.

> More information: <https://manned.org/run-mailcap>.

- Individual actions/programs on run-mailcap can be invoked with action flag:

```bash
run-mailcap --action=ACTION [--option[=value]]
```

- In simple language:

```bash
run-mailcap --action=ACTION filename
```

- Turn on extra information:

```bash
run-mailcap --action=ACTION --debug filename
```

- Ignore any "copiousoutput" directive and forward output to standard output:

```bash
run-mailcap --action=ACTION --nopager filename
```

- Display the found command without actually executing it:

```bash
run-mailcap --action=ACTION --norun filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: change Unicode characters to ASCII (#2802) Change Unicode characters to ASCII: - non-breaking spaces (\xc2\xa0) to [...] | 2019-02-25T00:56:24 | [6956cd5348e4](https://github.com/tldr-pages/tldr/commit/6956cd5348e4f87db1586a68ab299e46f7384b63)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | run-mailcup: run-mailcup, compose, edit, print, see commands (thanks to @flouthoc) | 2016-02-04T18:02:50 | [027402e8e7c4](https://github.com/tldr-pages/tldr/commit/027402e8e7c488cec64da1dbb317c02bdad79442)

