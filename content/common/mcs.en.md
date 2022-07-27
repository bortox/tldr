---
author: ['Emily Grace Seville']
date: 1647683816
title: "mcs, TLDR Pages"
description: "mcs, Mono C# Compiler."
categories: "common"
---
> More information: <https://manned.org/mcs.1>.

- Compile the specified files:

```bash
mcs path/to/input_file1.cs path/to/input_file2.cs ...
```

- Specify the output program name:

```bash
mcs -out:path/to/file.exe path/to/input_file1.cs path/to/input_file2.cs ...
```

- Specify the output program type:

```bash
mcs -target:exe|winexe|library|module path/to/input_file1.cs path/to/input_file2.cs ...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | mcs: add page (#7897) * Create mcs page: - closes #7418 * Use ellipsis | 2022-03-19T10:56:56 | [53cb52dbbb06](https://github.com/tldr-pages/tldr/commit/53cb52dbbb06e526eb138b4a3f79319f4ee2a594)

