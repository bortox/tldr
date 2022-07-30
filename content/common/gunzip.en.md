---
author: ['Waldir Pimenta', 'marchersimon', 'Agniva De Sarker', 'Laurent Indermühle']
date: 1626732787
title: "gunzip"
description: "gunzip, Extract file(s) from a gzip (.gz) archive."
categories: "common"
---
> More information: <https://manned.org/gunzip>.

- Extract a file from an archive, replacing the original file if it exists:

```bash
gunzip archive.tar.gz
```

- Extract a file to a target destination:

```bash
gunzip --stdout archive.tar.gz > archive.tar
```

- Extract a file and keep the archive file:

```bash
gunzip --keep archive.tar.gz
```

- List the contents of a compressed file:

```bash
gunzip --list file.txt.gz
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Laurent Indermühle](mailto:honiix@pm.me) | gunzip: add command to keep original files (#6247) | 2021-07-20T00:13:07 | [0e1a6e39f23b](https://github.com/tldr-pages/tldr/commit/0e1a6e39f23b1d16296eeb16a81a6603ca18b144)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | minor tweaks to gunzip.md, for improved clarity (#919) | 2016-06-21T09:09:40 | [698eacdb4407](https://github.com/tldr-pages/tldr/commit/698eacdb44072668ce1e82924256c5cfecd33f19)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | gunzip: add page (#909) | 2016-06-21T01:00:19 | [7f168f6144fb](https://github.com/tldr-pages/tldr/commit/7f168f6144fb0f25fb2c82cf255aa3b301398040)

