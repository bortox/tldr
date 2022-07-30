---
author: ['bl-ue']
date: 1610108139
title: "git check-attr"
description: "git check-attr, For every pathname, list if each attribute is unspecified, set, or unset as a gitattribute on that pathname."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-check-attr>.

- Check the values of all attributes on a file:

```bash
git check-attr --all path/to/file
```

- Check the value of a specific attribute on a file:

```bash
git check-attr attribute path/to/file
```

- Check the value of a specific attribute on files:

```bash
git check-attr --all path/to/file1 path/to/file2
```

- Check the value of a specific attribute on one or more files:

```bash
git check-attr attribute path/to/file1 path/to/file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-check-attr: add page (#5098) | 2021-01-08T13:15:39 | [2ec5fb9d5022](https://github.com/tldr-pages/tldr/commit/2ec5fb9d50226666ecc3dba0e697387c49d5a8d0)

