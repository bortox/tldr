---
author: ['DreamPiggy', 'Al Berez', 'pxgamer', 'Miguel Mendes', 'Gurdit Singh Bedi', 'Seth Falco', 'Ruben Vereecken']
date: 1629050349
title: "aria2c"
description: "aria2c, Fast download utility."
categories: "common"
---
> Supports HTTP(S), FTP, SFTP, BitTorrent, and Metalink.

> More information: <https://aria2.github.io>.

- Download a URI to a file:

```bash
aria2c url
```

- Download the file pointed to by the specified URI with the specified output name:

```bash
aria2c --out=filename url
```

- Download multiple files in parallel:

```bash
aria2c --force-sequential url_1 url_2
```

- Download from multiple sources with each URI pointing to the same file:

```bash
aria2c url_1 url_2
```

- Download the URIs listed in a file with limited parallel downloads:

```bash
aria2c --input-file=filename --max-concurrent-downloads=number_of_downloads
```

- Download with multiple connections:

```bash
aria2c --split=number_of_connections url
```

- FTP download with username and password:

```bash
aria2c --ftp-user=username --ftp-passwd=password url
```

- Limit download speed in bytes/s:

```bash
aria2c --max-download-limit=speed url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Gurdit Singh Bedi](mailto:gurditsbedi@gmail.com) | aria2c: add --force-sequential example and clarify default behavior (#5914) | 2021-05-11T16:46:41 | [9909eb3d14ec](https://github.com/tldr-pages/tldr/commit/9909eb3d14ec1a7b2fe93ebfb5bc344cc397d1c5)
[Al Berez](mailto:a-b@users.noreply.github.com) | aria2c: how to specify destination filename (#4334) | 2020-09-13T17:26:37 | [383fd1c2b903](https://github.com/tldr-pages/tldr/commit/383fd1c2b90385dbf010b838bf6d68af3f62210c)
[pxgamer](mailto:owzie123@gmail.com) | aria2c: add link to homepage | 2019-06-09T18:53:49 | [430af75de3f5](https://github.com/tldr-pages/tldr/commit/430af75de3f58f1692cadcc6d2616c99d8a6c5a3)
[Miguel Mendes](mailto:mendesmiguel@users.noreply.github.com) | aria2c: add new example (#2515) | 2018-10-29T17:59:22 | [840d3f2dd96a](https://github.com/tldr-pages/tldr/commit/840d3f2dd96a6bdd24d43ae78179c0c297008640)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted aria2c | 2016-01-21T12:45:39 | [b470ee397b1c](https://github.com/tldr-pages/tldr/commit/b470ee397b1c75652801c04a3ef3702be2987215)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | aria2c: Removed unneeded example and reworded | 2016-01-21T12:45:07 | [5ae1cf61673d](https://github.com/tldr-pages/tldr/commit/5ae1cf61673dd773fe02f2c5ccd624a042c991b6)
[DreamPiggy](mailto:lizhuoli1126@126.com) | add aria2c aria2c: add | 2016-01-05T09:44:47 | [2cd638027d7e](https://github.com/tldr-pages/tldr/commit/2cd638027d7e940263091e63e9fd0d467ad0bec1)

