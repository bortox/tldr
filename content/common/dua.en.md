---
author: ['siavashsoleymani', 'Thamaraiselvam']
date: 1603796471
title: "dua"
description: "dua, Dua (Disk Usage Analyzer) is a tool to conveniently learn about the usage of disk space of a given directory."
categories: "common"
---
> More information: <https://github.com/Byron/dua-cli>.

- Analyze specific directory:

```bash
dua path/to/directory
```

- Display apparent size instead of disk usage:

```bash
dua --apparent-size
```

- Count hard-linked files each time they are seen:

```bash
dua --count-hard-links
```

- Aggregate the consumed space of one or more directories or files:

```bash
dua aggregate
```

- Launch the terminal user interface:

```bash
dua interactive
```

- Format printing byte counts:

```bash
dua --format metric|binary|bytes|GB|GiB|MB|MiB
```

- Set the number of threads to be used:

```bash
dua --threads count
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[siavashsoleymani](mailto:siavash.solimanii@yahoo.com) | dua: fix typo | 2020-10-27T12:01:11 | [2ceaa0eb6656](https://github.com/tldr-pages/tldr/commit/2ceaa0eb66561ca74c7dd446b9bb052ff4778769)
[Thamaraiselvam](mailto:thamaraiselvam@live.com) | dua: add page (#4393) | 2020-10-05T17:15:21 | [89ef5b77a6b2](https://github.com/tldr-pages/tldr/commit/89ef5b77a6b24e9489f075f9b7343b7c1ca2e260)

