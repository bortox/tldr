---
author: ['Emily Grace Seville']
date: 1650077428
title: "mate-search-tool, TLDR Pages"
description: "mate-search-tool, Search files in MATE desktop environment."
categories: "linux"
---
> More information: <https://manned.org/mate-search-tool>.

- Search files containing a specific string in their name in a specific directory:

```bash
mate-search-tool --named=string --path=path/to/directory
```

- Search files without waiting a user confirmation:

```bash
mate-search-tool --start --named=string --path=path/to/directory
```

- Search files with name matching a specific regular expression:

```bash
mate-search-tool --start --regex=string --path=path/to/directory
```

- Set a sorting order in search results:

```bash
mate-search-tool --start --named=string --path=path/to/directory --sortby=name|folder|size|type|date
```

- Set a descending sorting order:

```bash
mate-search-tool --start --named=string --path=path/to/directory --descending
```

- Search files owned by a specific user/group:

```bash
mate-search-tool --start --user|group=value --path=path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | mate-search-tool: add page (#8016) | 2022-04-16T04:50:28 | [b1e210a98fef](https://github.com/tldr-pages/tldr/commit/b1e210a98fef4d828046016e510978ee4cd2a917)

