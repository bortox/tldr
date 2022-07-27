---
author: ['Ein Verne']
date: 1597188754
title: "scc, TLDR Pages"
description: "scc, Tool written in Go that counts lines of code."
categories: "common"
---
> More information: <https://github.com/boyter/scc>.

- Print lines of code in the current directory:

```bash
scc
```

- Print lines of code in the target directory:

```bash
scc path/to/directory
```

- Display output for every file:

```bash
scc --by-file
```

- Display output using a specific output format (defaults to `tabular`):

```bash
scc --format tabular|wide|json|csv|cloc-yaml|html|html-table
```

- Only count files with specific file extensions:

```bash
scc --include-ext go, java, js
```

- Exclude directories from being counted:

```bash
scc --exclude-dir .git,.hg
```

- Display output and sort by column (defaults to by files):

```bash
scc --sort files|name|lines|blanks|code|comments|complexity
```

- Print help for scc:

```bash
scc -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | scc: add page (#4248) | 2020-08-12T01:32:34 | [6461fb63f29d](https://github.com/tldr-pages/tldr/commit/6461fb63f29d03b44517926eba6721136d142487)

