---
author: ['Alex Martens']
date: 1661034785
title: "unzstd"
description: "unzstd, Decompress files with Zstandard compression."
categories: "common"
---
> More information: <https://github.com/facebook/zstd>.

- Decompress files:

```bash
unzstd path/to/file1.ztd path/to/file2.ztd ...
```

- Decompress a file into a specific output file:

```bash
unzstd path/to/compressed.ztd -o path/to/extracted_file
```

- Display information about a compressed file:

```bash
unzip --list path/to/file.zst
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex Martens](mailto:alex@thinglab.org) | unzstd: add page (#8385) | 2022-08-21T00:33:05 | [25a2a44a01f6](https://github.com/tldr-pages/tldr/commit/25a2a44a01f6b378b723845ee47b5cd9b65cd839)

