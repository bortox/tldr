---
author: ['Pierre Rudloff']
date: 1589468843
title: "quilt"
description: "quilt, Tool to manage a series of patches."
categories: "common"
---
> More information: <https://savannah.nongnu.org/projects/quilt>.

- Import an existing patch from a file:

```bash
quilt import path/to/filename.patch
```

- Create a new patch:

```bash
quilt new filename.patch
```

- Add a file to the current patch:

```bash
quilt add path/to/file
```

- After editing the file, refresh the current patch with the changes:

```bash
quilt refresh
```

- Apply all the patches in the series file:

```bash
quilt push -a
```

- Remove all applied patches:

```bash
quilt pop -a
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | debchange, debuild, dget, quilt: add pages (#4022) | 2020-05-14T17:07:23 | [20f4b567344a](https://github.com/tldr-pages/tldr/commit/20f4b567344aee07be76c6f6c440aef99cec69b3)

