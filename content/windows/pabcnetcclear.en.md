---
author: ['Emily Grace Seville']
date: 1649076388
title: "pabcnetcclear"
description: "pabcnetcclear, Preprocess and compile PascalABC.NET source files."
categories: "windows"
---
> More information: <http://pascalabc.net>.

- Compile the specified source file into an executable with the same name:

```bash
pabcnetcclear path/to/source_file.pas
```

- Compile the specified source file into an executable with the specified name:

```bash
pabcnetcclear /Output:path/to/file.pas path/to/source_file.pas
```

- Compile the specified source file into an executable with the same name along with/without debug information:

```bash
pabcnetcclear /Debug:0|1 path/to/source_file.pas
```

- Allow units to be searched in the specified path while compiling the source file into an executable with the same name:

```bash
pabcnetcclear /SearchDir:path/to/dir path/to/source_file.pas
```

- Compile the specified source file into an executable, defining a symbol:

```bash
pabcnetcclear /Define:symbol path/to/source_file.pas
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | Better grammar in pabcnetcclear (#7934) | 2022-04-04T14:46:28 | [213dab9463b8](https://github.com/tldr-pages/tldr/commit/213dab9463b85be26988530de244b05c563c2bb4)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | pabcnetcclear: update page (#7532) | 2022-01-02T21:30:53 | [58f6f4124ea1](https://github.com/tldr-pages/tldr/commit/58f6f4124ea11f2e90a737dae4febfd62173146c)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | pabcnetcclear: add page (#7412) | 2021-11-14T20:10:47 | [0dfceab76bd6](https://github.com/tldr-pages/tldr/commit/0dfceab76bd62a5b5d34bc7c4979250f4ca19a7e)

