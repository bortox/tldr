---
author: ['Ethan Kinnear']
date: 1658419640
title: "cot, TLDR Pages"
description: "cot, The Plain-Text Editor for macOS."
categories: "osx"
---
> More information: <https://coteditor.com/>.

- Start CotEditor:

```bash
cot
```

- Open specific files:

```bash
cot path/to/file1 path/to/file2 ...
```

- Open a new blank document:

```bash
cot --new
```

- Open a specific file and block the terminal until it is closed:

```bash
cot --wait path/to/file
```

- Open a specific file with the cursor at a specific line and column:

```bash
cot --line line_number --column column_number path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ethan Kinnear](mailto:contact@superatomic.dev) | cot: add page (#8205) * cot: add page * cot: fix name of command * cot: change "done" to "finished" * Update pages/osx/cot.md Co- [...] | 2022-07-21T18:07:20 | [ee5e55861313](https://github.com/tldr-pages/tldr/commit/ee5e558613133da89efa96b58f578cdf9af76a9e)

