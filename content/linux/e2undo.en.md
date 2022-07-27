---
author: ['Axel Navarro']
date: 1609780047
title: "e2undo, TLDR Pages"
description: "e2undo, Replay undo logs for an ext2/ext3/ext4 filesystem."
categories: "linux"
---
> This can be used to undo a failed operation by an e2fsprogs program.

> More information: <https://man7.org/linux/man-pages/man8/e2undo.8.html>.

- Display information about a specific undo file:

```bash
e2undo -h path/to/undo_file /dev/sdXN
```

- Perform a dry-run and display the candidate blocks for replaying:

```bash
e2undo -nv path/to/undo_file /dev/sdXN
```

- Perform an undo operation:

```bash
e2undo path/to/undo_file /dev/sdXN
```

- Perform an undo operation and display verbose information:

```bash
e2undo -v path/to/undo_file /dev/sdXN
```

- Write the old contents of the block to an undo file before overwriting a file system block:

```bash
e2undo -z path/to/file.e2undo path/to/undo_file /dev/sdXN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | e2undo: add page (#5074) | 2021-01-04T18:07:27 | [39e5e04e4a67](https://github.com/tldr-pages/tldr/commit/39e5e04e4a67ab9ad9c0298de08ab55c0e62e55e)

