---
author: ['Ein Verne']
date: 1581974843
title: "jdupes, TLDR Pages"
description: "jdupes, A powerful duplicate file finder and an enhanced fork of fdupes."
categories: "common"
---
> More information: <https://github.com/jbruchon/jdupes>.

- Search a single directory:

```bash
jdupes directory
```

- Search multiple directories:

```bash
jdupes directory1 directory2
```

- Search all directories recursively:

```bash
jdupes --recurse directory
```

- Search directory recursively and let user choose files to preserve:

```bash
jdupes --delete --recurse directory
```

- Search multiple directories and follow subdirectores under directory2, not directory1:

```bash
jdupes directory1 --recurse: directory2
```

- Search multiple directories and keep the directory order in result:

```bash
jdupes -O directory1 directory2 directory3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | jdupes: add page (#3857) | 2020-02-17T22:27:23 | [519edc9bf067](https://github.com/tldr-pages/tldr/commit/519edc9bf0679395da40627b8cf68dd231827049)

