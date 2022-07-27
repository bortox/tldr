---
author: ['chris']
date: 1629042367
title: "lipo, TLDR Pages"
description: "lipo, Tool for handling Mach-O Universal Binaries."
categories: "osx"
---
> More information: <https://ss64.com/osx/lipo.html>.

- Create a universal file from two single-architecture files:

```bash
lipo path/to/binary.x86_64 path/to/binary.arm64e -create -output path/to/binary
```

- List all architectures contained in a universal file:

```bash
lipo path/to/binary -archs
```

- Display detailed information about a universal file:

```bash
lipo path/to/binary -detailed_info
```

- Extract a single-architecture file from a universal file:

```bash
lipo path/to/binary -thin arm64e -output path/to/binary.arm64e
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[chris](mailto:35269695+chrissxYT@users.noreply.github.com) | lipo: add page (#6306) | 2021-08-15T17:46:07 | [ff3692c00517](https://github.com/tldr-pages/tldr/commit/ff3692c005172895c260f15a6d153a9fe30323e9)

