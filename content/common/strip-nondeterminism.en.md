---
author: ['Juri']
date: 1602538674
title: "strip-nondeterminism"
description: "strip-nondeterminism, A tool to remove non-deterministic information (e.g. timestamps) from files."
categories: "common"
---
> More information: <https://salsa.debian.org/reproducible-builds/strip-nondeterminism>.

- Strip nondeterministic information from a file:

```bash
strip-nondeterminism path/to/file
```

- Strip nondeterministic information from a file manually specifying the filetype:

```bash
strip-nondeterminism --type filetype path/to/file
```

- Strip nondeterministic information from a file; instead of removing timestamps set them to the specified UNIX timestamp:

```bash
strip-nondeterminism --timestamp unix_timestamp path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | strip-nondeterminism: add page (#4647) | 2020-10-12T23:37:54 | [8740bbc2bb5b](https://github.com/tldr-pages/tldr/commit/8740bbc2bb5b52d364fc48d25cd7a192bfa4d3f7)

