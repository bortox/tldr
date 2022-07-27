---
author: ['Gabri Botha']
date: 1650016100
title: "duc, TLDR Pages"
description: "duc, Duc is a collection of tools for indexing, inspecting and visualizing disk usage. Duc maintains a database of accumulated sizes of directories of the file system, allowing queries this database, or create fancy graphs to show where data is."
categories: "common"
---
> More information: <https://duc.zevv.nl/>.

- Index the /usr directory, writing to the default database location ~/.duc.db:

```bash
duc index /usr
```

- List all files and directories under /usr/local, showing relative file sizes in a [g]raph:

```bash
duc ls -Fg /usr/local
```

- List all files and directories under /usr/local using treeview recursively:

```bash
duc ls -Fg -R /usr/local
```

- Start the graphical interface to explore the file system using sunburst graphs:

```bash
duc gui /usr
```

- Run the ncurses console interface to explore the file system:

```bash
duc ui /usr
```

- Dump database info:

```bash
duc info
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gabri Botha](mailto:AngelODeath@outlook.com) | duc: add page (#7869) * Create duc.md Co-authored-by: Emily Grace Seville <emilyseville7cf@gmail.com> | 2022-04-15T11:48:20 | [870c73019138](https://github.com/tldr-pages/tldr/commit/870c73019138151a3abddc312ca37a32bcef9dd5)

