---
author: ['Pierre Rudloff']
date: 1589468843
title: "debchange"
description: "debchange, Tool for maintenance of the debian/changelog file in a Debian source package."
categories: "linux"
---
> More information: <https://manpages.debian.org/debchange>.

- Add a new version for a non-maintainer upload to the changelog:

```bash
debchange --nmu
```

- Add a changelog entry to the current version:

```bash
debchange --append
```

- Add a changelog entry to close the bug with specified ID:

```bash
debchange --closes bug_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | debchange, debuild, dget, quilt: add pages (#4022) | 2020-05-14T17:07:23 | [20f4b567344a](https://github.com/tldr-pages/tldr/commit/20f4b567344aee07be76c6f6c440aef99cec69b3)

