---
author: ['Axel Navarro']
date: 1636461640
title: "swc"
description: "swc, JavaScript and TypeScript compiler written in Rust."
categories: "common"
---
> More information: <https://swc.rs>.

- Transpile a specified input file and output to stdout:

```bash
swc path/to/file
```

- Transpile the input file every time it is changed:

```bash
swc path/to/file --watch
```

- Transpile a specified input file and output to a specific file:

```bash
swc path/to/input_file --out-file path/to/output_file
```

- Transpile a specified input directory and output to a specific directory:

```bash
swc path/to/input_directory --out-dir path/to/output_directory
```

- Transpile a specified input directory using a specific configuration file:

```bash
swc path/to/input_directory --config-file path/to/.swcrc
```

- Ignore files in a directory specified using glob path:

```bash
swc path/to/input_directory --ignore ignored_files
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | swc: add page (#7396) | 2021-11-09T13:40:40 | [1d0a5e9c0b5a](https://github.com/tldr-pages/tldr/commit/1d0a5e9c0b5a7c7bc07b4cff046ce5da91e9eb61)

