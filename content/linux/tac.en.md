---
author: ['Emily Grace Seville']
date: 1652466593
title: "tac, TLDR Pages"
description: "tac, Display and concatenate files with lines in reversed order."
categories: "linux"
---
> See also: `cat`.

> More information: <https://www.gnu.org/software/coreutils/tac>.

- Concatenate specific files in reversed order:

```bash
tac path/to/file1 path/to/file2 ...
```

- Display `stdin` in reversed order:

```bash
cat path/to/file | tac
```

- Use a specific separator:

```bash
tac --separator , path/to/file1 path/to/file2 ...
```

- Use a specific regex as a separator:

```bash
tac --regex --separator [,;] path/to/file1 path/to/file2 ...
```

- Use a separator before each file:

```bash
tac --before path/to/file1 path/to/file2 ...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | tac: refresh page (#8057) * More general descriptions and better title * Don't use `print` word * More specific verb in first sample [...] | 2022-05-13T20:29:53 | [e92c24d49dbd](https://github.com/tldr-pages/tldr/commit/e92c24d49dbde6bba88973727cc44e222afb8334)

