---
author: ['Simon B']
date: 1635516065
title: "git symbolic-ref"
description: "git symbolic-ref, Read, change, or delete files that store references."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-symbolic-ref>.

- Store a reference by a name:

```bash
git symbolic-ref refs/name ref
```

- Store a reference by name, including a message with a reason for the update:

```bash
git symbolic-ref -m "message" refs/name refs/heads/branch_name
```

- Read a reference by name:

```bash
git symbolic-ref refs/name
```

- Delete a reference by name:

```bash
git symbolic-ref --delete refs/name
```

- For scripting, hide errors with `--quiet` and use `--short` to simplify ("refs/heads/X" prints as "X"):

```bash
git symbolic-ref --quiet --short refs/name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Simon B](mailto:simon.bohlin@gmail.com) | git-symbolic-ref: add page (#6938) | 2021-10-29T16:01:05 | [510e695f9f33](https://github.com/tldr-pages/tldr/commit/510e695f9f33f77c663910476d28db4f4145a1f8)

