---
author: ['Emily Grace Seville']
date: 1660524792
title: "ed"
description: "ed, The original Unix text editor."
categories: "osx"
---
> See also: `awk`, `sed`.

> More information: <https://www.gnu.org/software/ed/manual/ed_manual.html>.

- Start an interactive editor session with an empty document:

```bash
ed
```

- Start an interactive editor session with an empty document and a specific [p]rompt:

```bash
ed -p '> '
```

- Start an interactive editor session with an empty document and without diagnostics, byte counts and '!' prompt:

```bash
ed -s
```

- Edit a specific file (this shows the byte count of the loaded file):

```bash
ed path/to/file
```

- Replace a string with a specific replacement for all lines:

```bash
,s/regular_expression/replacement/g
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | ed: refresh/add pages (#7933) * Update common/ed.md * Create osx/ed.md * Prefer `a specific` * Fix quoting in common/ed * Fix quoting [...] | 2022-08-15T02:53:12 | [e6fb17a014ba](https://github.com/tldr-pages/tldr/commit/e6fb17a014baf52f06f9171f16eff7e79fa62373)

