---
author: ['git-em']
date: 1647433060
title: "zlib-flate"
description: "zlib-flate, Raw zlib compression and decompression program."
categories: "common"
---
> Part of `qpdf`.

> More information: <https://manned.org/zlib-flate>.

- Compress a file:

```bash
zlib-flate -compress < path/to/input_file > path/to/compressed.zlib
```

- Uncompress a file:

```bash
zlib-flate -uncompress < path/to/compressed.zlib > path/to/output_file
```

- Compress a file with a specified compression level. 0=Fastest (Worst), 9=Slowest (Best):

```bash
zlib-flate -compress=compression_level < path/to/input_file > path/to/compressed.zlib
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | zlib-flate: add page (#7839) | 2022-03-16T13:17:40 | [c23e529ad225](https://github.com/tldr-pages/tldr/commit/c23e529ad225fed016c79bed116bdf6266fcdef9)

