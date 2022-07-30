---
author: ['Janek', 'Emily Grace Seville']
date: 1637593475
title: "getopt"
description: "getopt, Parse command line arguments."
categories: "linux"
---
> More information: <https://www.gnu.org/software/libc/manual/html_node/Getopt.html>.

- Parse optional `verbose`/`version` flags with shorthands:

```bash
getopt --options vV --longoptions verbose,version -- --version --verbose
```

- Add a `--file` option with a required argument with shorthand `-f`:

```bash
getopt --options f: --longoptions file: -- --file=somefile
```

- Add a `--verbose` option with an optional argument with shorthand `-v`, and pass a non-option parameter `arg`:

```bash
getopt --options v:: --longoptions verbose:: -- --verbose arg
```

- Accept a `-r` and `--verbose` flag, a `--accept` option with an optional argument and add a `--target` with a required argument option with shorthands:

```bash
getopt --options rv::s::t: --longoptions verbose,source::,target: -- -v --target target
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | getopt: use long argument for --options | 2021-11-22T16:04:35 | [a22424ffdd91](https://github.com/tldr-pages/tldr/commit/a22424ffdd917ea843ea6d59b709aa00ea243448)
[Janek](mailto:27jf@pm.me) | getopt: add page (#6990) | 2021-10-23T20:36:21 | [e9045f60a5e3](https://github.com/tldr-pages/tldr/commit/e9045f60a5e3a6cc859651aaae61cd23f4b53a8f)

