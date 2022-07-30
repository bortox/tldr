---
author: ['Waldir Pimenta', 'Dario Vladović', 'Emily Grace Seville', 'Agniva De Sarker', 'rprieto', 'Bruno Durán', 'shyneko', 'Ruben Vereecken', 'Steve Stodola', 'marchersimon']
date: 1642903608
title: "tail"
description: "tail, Display the last part of a file."
categories: "common"
---
> See also: `head`.

> More information: <https://www.gnu.org/software/coreutils/tail>.

- Show last 'count' lines in file:

```bash
tail --lines count path/to/file
```

- Print a file from a specific line number:

```bash
tail --lines +count path/to/file
```

- Print a specific count of bytes from the end of a given file:

```bash
tail --bytes count path/to/file
```

- Print the last lines of a given file and keep reading file until `Ctrl + C`:

```bash
tail --follow path/to/file
```

- Keep reading file until `Ctrl + C`, even if the file is inaccessible:

```bash
tail --retry --follow path/to/file
```

- Show last 'num' lines in 'file' and refresh every 'n' seconds:

```bash
tail --lines count --sleep-interval seconds --follow path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | tail: refresh page (#7681) | 2022-01-23T03:06:48 | [27033a5d95e7](https://github.com/tldr-pages/tldr/commit/27033a5d95e75de947f910e2a7a4d7e98804462f)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tail: fix wording (#7390) | 2021-11-07T20:00:19 | [34bc4af530d8](https://github.com/tldr-pages/tldr/commit/34bc4af530d81411a5a9bbe903782abd71fba180)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tail: add more information link (#5595) | 2021-03-30T15:49:07 | [b265ecca7b89](https://github.com/tldr-pages/tldr/commit/b265ecca7b89c98edac77c43c920e411e01539d9)
[shyneko](mailto:34548743+tminei@users.noreply.github.com) | tail: add example using -s parameter. (#4180) | 2020-07-16T22:49:40 | [94cb11e58d95](https://github.com/tldr-pages/tldr/commit/94cb11e58d95084384cf71200910bd336439b0a5)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | add a comma | 2017-11-24T07:11:53 | [29612adca2f2](https://github.com/tldr-pages/tldr/commit/29612adca2f2f57d6a2fcf372fd2c322b55f8a15)
[Steve Stodola](mailto:sstodola@plytro.com) | Update tail.md | 2017-11-24T06:53:55 | [5174bb40f6cc](https://github.com/tldr-pages/tldr/commit/5174bb40f6cc4dee0e08c23d6d40cc022ebe04d9)
[Steve Stodola](mailto:sstodola@plytro.com) | update tail to indicate -F If I open the file with tail like this: $ tail -f /var/log/messages ... and if the log rotation facility on [...] | 2017-11-24T01:16:08 | [2c789950db27](https://github.com/tldr-pages/tldr/commit/2c789950db2777cac6d87de9312405b804a9025c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | change all keyboard shortcuts to have spaces around the + sign (#1356) | 2017-04-29T00:34:51 | [433370e2ad4c](https://github.com/tldr-pages/tldr/commit/433370e2ad4c946240af47231397315eb803695f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | standardize format of keyboard shortcuts (#1354) * fix capitalization of keyboard shortcuts (elinks, tmux, screen) * adjust formatting [...] | 2017-04-28T09:44:50 | [7e1f06ade4d8](https://github.com/tldr-pages/tldr/commit/7e1f06ade4d869f8c1690fd04c25d8476c46b198)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Bruno Durán](mailto:bruno.duran.rey@gmail.com) | Improved tail.md | 2014-03-19T12:49:24 | [57d42257d32f](https://github.com/tldr-pages/tldr/commit/57d42257d32f7605205e1291b439263cfd59ec23)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

