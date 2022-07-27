---
author: ['Starbeamrainbowlabs']
date: 1617535619
title: "compsize, TLDR Pages"
description: "compsize, Calculate the compression ratio of a set of files on a btrfs filesystem."
categories: "linux"
---
> See also `btrfs filesystem` for recompressing a file by defragmenting it.

> More information: <https://github.com/kilobyte/compsize>.

- Calculate the current compression ratio for a file or directory:

```bash
sudo compsize path/to/file_or_directory
```

- Don't traverse filesystem boundaries:

```bash
sudo compsize --one-file-system path/to/file_or_directory
```

- Show raw byte counts instead of human-readable sizes:

```bash
sudo compsize --bytes path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | compsize: add page (#5685) | 2021-04-04T13:26:59 | [fc2f11810333](https://github.com/tldr-pages/tldr/commit/fc2f118103338f7f30b40cc7d5a61974fefa4650)

