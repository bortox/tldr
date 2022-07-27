---
author: ['MT']
date: 1580385691
title: "p7zip, TLDR Pages"
description: "p7zip, Wrapper of 7-Zip file archiver with high compression ratio."
categories: "common"
---
> Internally executes either 7za or 7zr command.

> More information: <http://p7zip.sourceforge.net>.

- Archive a file, replacing it with a 7zipped compressed version:

```bash
p7zip path/to/file
```

- Archive a file keeping the input file:

```bash
p7zip -k path/to/file
```

- Decompress a file, replacing it with the original uncompressed version:

```bash
p7zip -d compressed.ext.7z
```

- Decompress a file keeping the input file:

```bash
p7zip -d -k compressed.ext.7z
```

- Skip some checks and force compression or decompression:

```bash
p7zip -f path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[MT](mailto:59728838+mt-empty@users.noreply.github.com) | p7zip: add page (#3813) | 2020-01-30T13:01:31 | [031efda8d125](https://github.com/tldr-pages/tldr/commit/031efda8d125cb43acb638b150e9670f0c544694)

