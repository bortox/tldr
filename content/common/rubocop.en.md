---
author: ['Emily Grace Seville']
date: 1644837703
title: "rubocop, TLDR Pages"
description: "rubocop, Lint Ruby files."
categories: "common"
---
> More information: <https://docs.rubocop.org/rubocop/usage/basic_usage.html>.

- Check all files in the current directory (including subdirectories):

```bash
rubocop
```

- Check one or more specific files or directories:

```bash
rubocop path/to/file path/to/directory
```

- Write output to file:

```bash
rubocop --out path/to/file
```

- View list of cops (linter rules):

```bash
rubocop --show-cops
```

- Exclude a cop:

```bash
rubocop --except cop_1 cop_2
```

- Run only specified cops:

```bash
rubocop --only cop_1 cop_2
```

- Auto-correct files (experimental):

```bash
rubocop --auto-correct
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)

