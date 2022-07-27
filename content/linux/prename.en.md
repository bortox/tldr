---
author: ['Arthur Bols', 'Emily Grace Seville']
date: 1647882468
title: "rename, TLDR Pages"
description: "rename, Rename multiple files."
categories: "linux"
---
> NOTE: this page refers to the command from the `prename` Fedora package.

> More information: <https://manned.org/man/prename>.

- Rename files using a Perl Common Regular Expression (substitute 'foo' with 'bar' wherever found):

```bash
rename 's/foo/bar/' *
```

- Dry-run - display which renames would occur without performing them:

```bash
rename -n 's/foo/bar/' *
```

- Force renaming even if the operation would remove existing destination files:

```bash
rename -f 's/foo/bar/' *
```

- Convert filenames to lower case (use `-f` in case-insensitive filesystems to prevent "already exists" errors):

```bash
rename 'y/A-Z/a-z/' *
```

- Replace whitespace with underscores:

```bash
rename 's/\s+/_/g' *
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Arthur Bols](mailto:arthur@bols.dev) | rename: address different versions of the command (#3126) Address the presence of multiple and different versions of the rename [...] | 2019-07-18T14:08:48 | [89c43ca8e4a5](https://github.com/tldr-pages/tldr/commit/89c43ca8e4a556052f937be31325a552002af4f3)

