---
author: ['Austin', 'sedrubal']
date: 1601735886
title: "duperemove, TLDR Pages"
description: "duperemove, Finds duplicate filesystem extents and optionally schedule them for deduplication."
categories: "linux"
---
> An extent is small part of a file inside the filesystem.

> On some filesystems one extent can be referenced multiple times, when parts of the content of the files are identical.

> More information: <https://markfasheh.github.io/duperemove/>.

- Search for duplicate extents in a directory and show them:

```bash
duperemove -r path/to/directory
```

- Deduplicate duplicate extents on a Btrfs or XFS (experimental) filesystem:

```bash
duperemove -r -d path/to/directory
```

- Use a hash file to store extent hashes (less memory usage and can be reused on subsequent runs):

```bash
duperemove -r -d --hashfile=path/to/hashfile path/to/directory
```

- Limit I/O threads (for hashing and dedupe stage) and CPU threads (for duplicate extent finding stage):

```bash
duperemove -r -d --hashfile=path/to/hashfile --io-threads=N --cpu-threads=N path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | cryfs, df, dfc, fls, ipfs, duperemove, edquote, lsattr, diskutil: (#4427) consistently use "filesystem" | 2020-10-03T16:38:06 | [cfe462c57f20](https://github.com/tldr-pages/tldr/commit/cfe462c57f20c344dad34717378c442dc32cadc2)
[sedrubal](mailto:sedrubal@users.noreply.github.com) | duperemove: add page (#4231) | 2020-08-01T19:33:41 | [d36da71fb696](https://github.com/tldr-pages/tldr/commit/d36da71fb6961cafb4c475f85558efe41e68691c)

