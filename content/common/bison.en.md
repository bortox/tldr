---
author: ['Starbeamrainbowlabs']
date: 1577846655
title: "bison"
description: "bison, GNU parser generator."
categories: "common"
---
> More information: <https://www.gnu.org/software/bison/>.

- Compile a bison definition file:

```bash
bison path/to/file.y
```

- Compile in debug mode, which causes the resulting parser to write additional information to the standard output:

```bash
bison --debug path/to/file.y
```

- Specify the output filename:

```bash
bison --output path/to/output.c path/to/file.y
```

- Be verbose when compiling:

```bash
bison --verbose
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | bison: add page (#3722) | 2020-01-01T03:44:15 | [eb0fe6392b40](https://github.com/tldr-pages/tldr/commit/eb0fe6392b406b948ff1492d335cad9b95cb35c6)

