---
author: ['Arthur Bols', 'Emily Grace Seville']
date: 1647882468
title: "rename, TLDR Pages"
description: "rename, Rename multiple files."
categories: "linux"
---
> NOTE: this page refers to the command from the `util-linux` package.

> For the Perl version, see `file-rename` or `perl-rename`.

> Warning: This command has no safeguards and will overwrite files without prompting.

> More information: <https://manned.org/rename>.

- Rename files using simple substitutions (substitute 'foo' with 'bar' wherever found):

```bash
rename foo bar *
```

- Dry-run - display which renames would occur without performing them:

```bash
rename -vn foo bar *
```

- Do not overwrite existing files:

```bash
rename -o foo bar *
```

- Change file extensions:

```bash
rename .ext .bak *.ext
```

- Prepend "foo" to all filenames in the current directory:

```bash
rename '' 'foo' *
```

- Rename a group of increasingly numbered files zero-padding the numbers up to 3 digits:

```bash
rename foo foo00 foo? && rename foo foo0 foo??
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Arthur Bols](mailto:arthur@bols.dev) | rename: address different versions of the command (#3126) Address the presence of multiple and different versions of the rename [...] | 2019-07-18T14:08:48 | [89c43ca8e4a5](https://github.com/tldr-pages/tldr/commit/89c43ca8e4a556052f937be31325a552002af4f3)

