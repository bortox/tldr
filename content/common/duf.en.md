---
author: ['walking-octopus']
date: 1658322200
title: "duf"
description: "duf, Disk Usage/Free Utility."
categories: "common"
---
> More information: <https://github.com/muesli/duf>.

- List accessible devices:

```bash
duf
```

- List everything (such as pseudo, duplicate or inaccessible file systems):

```bash
duf --all
```

- Only show specified devices or mount points:

```bash
duf path/to/directory1 path/to/directory2 ...
```

- Sort the output by a specified criteria:

```bash
duf --sort size|used|avail|usage
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[walking-octopus](mailto:46994949+walking-octopus@users.noreply.github.com) | duf: add page (#8171) | 2022-07-20T15:03:20 | [6710d757da06](https://github.com/tldr-pages/tldr/commit/6710d757da06fb31d3a01ada4eaa81047f4e49e2)

