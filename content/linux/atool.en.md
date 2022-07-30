---
author: ['Anirudh Haritas Murali', 'Emily Grace Seville']
date: 1647715012
title: "atool"
description: "atool, Manage archives of various formats."
categories: "linux"
---
> More information: <https://www.nongnu.org/atool/>.

- List files in a zip archive:

```bash
atool --list path/to/archive.zip
```

- Unpack a tar.gz archive into a new subdirectory (or current directory if it contains only one file):

```bash
atool --extract path/to/archive.tar.gz
```

- Create a new 7zip archive with two files:

```bash
atool --add path/to/archive.7z path/to/file1 path/to/file2 ...
```

- Extract all zip and rar archives in the current directory:

```bash
atool --each --extract *.zip *.rar
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | atool: update page (#7900) | 2022-03-19T19:36:52 | [90c380774609](https://github.com/tldr-pages/tldr/commit/90c380774609443461275b08ddcd5bf8b31b749a)
[Anirudh Haritas Murali](mailto:49116134+anihm136@users.noreply.github.com) | atool: add page (#6901) | 2021-10-09T07:36:35 | [92a69cad6e45](https://github.com/tldr-pages/tldr/commit/92a69cad6e456833b1ee83cb05025130a6d1243a)

