---
author: ['CleanMachine1']
date: 1624991646
title: "git verify-tag"
description: "git verify-tag, Check for GPG verification of tags."
categories: "common"
---
> If a tag wasn't signed, an error will occur.

> More information: <https://git-scm.com/docs/git-verify-tag>.

- Check tags for a GPG signature:

```bash
git verify-tag tag1 optional_tag2 ...
```

- Check tags for a GPG signature and show details for each tag:

```bash
git verify-tag tag1 optional_tag2 ... --verbose
```

- Check tags for a GPG signature and print the raw details:

```bash
git verify-tag tag1 optional_tag2 ... --raw
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | git-verify-tag: add page (#6139) | 2021-06-29T20:34:06 | [cc755655a3bc](https://github.com/tldr-pages/tldr/commit/cc755655a3bce30cd342654cc1f2be5ef952f788)

