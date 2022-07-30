---
author: ['Inias Peeters', 'Stig124', 'Arthur Bols']
date: 1641575142
title: "rename"
description: "rename, Rename multiple files."
categories: "linux"
---
> NOTE: this page refers to the command from the `rename` Debian package.

> More information: <https://manned.org/file-rename>.

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
[Inias Peeters](mailto:iniasp@gmail.com) | file-rename: fix Debian package name (#7618) | 2022-01-07T18:05:42 | [210dc2e1869c](https://github.com/tldr-pages/tldr/commit/210dc2e1869cd0bf2266240f4a0035ba9cb40488)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Arthur Bols](mailto:arthur@bols.dev) | rename: address different versions of the command (#3126) Address the presence of multiple and different versions of the rename [...] | 2019-07-18T14:08:48 | [89c43ca8e4a5](https://github.com/tldr-pages/tldr/commit/89c43ca8e4a556052f937be31325a552002af4f3)

