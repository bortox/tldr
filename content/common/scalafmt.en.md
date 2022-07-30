---
author: ['elia migliore']
date: 1634425290
title: "scalafmt"
description: "scalafmt, Code formatter for Scala."
categories: "common"
---
> Configurations are stored in the `.scalafmt.conf` file.

> More information: <https://scalameta.org/scalafmt>.

- Reformat all `.scala` files in the current directory recursively:

```bash
scalafmt
```

- Reformat specific files or directories with a custom formatting configuration:

```bash
scalafmt --config path/to/.scalafmt.conf path/to/file_or_directory path/to/file_or_directory ...
```

- Check if files are correctly formatted, returning `0` if all files respect the formatting style:

```bash
scalafmt --config path/to/.scalafmt.conf --test
```

- Exclude files or directories:

```bash
scalafmt --exclude path/to/file_or_directory ...
```

- Format only files that were edited against the current Git branch:

```bash
scalafmt --config path/to/.scalafmt.conf --mode diff
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[elia migliore](mailto:migliorelia@gmail.com) | scalafmt: add page (#6808) | 2021-10-17T01:01:30 | [96970ddbefd2](https://github.com/tldr-pages/tldr/commit/96970ddbefd23089d3d9647e4825fbf2655afd3c)

