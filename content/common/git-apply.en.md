---
author: ['Axel Navarro']
date: 1597188833
title: "git apply"
description: "git apply, Apply a patch to files and/or to the index."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-apply>.

- Print messages about the patched files:

```bash
git apply --verbose path/to/file
```

- Apply and add the patched files to the index:

```bash
git apply --index path/to/file
```

- Apply a remote patch file:

```bash
curl https://example.com/file.patch | git apply
```

- Output diffstat for the input and apply the patch:

```bash
git apply --stat --apply path/to/file
```

- Apply the patch in reverse:

```bash
git apply --reverse path/to/file
```

- Store the patch result in the index without modifying the working tree:

```bash
git apply --cache path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-apply: add page (#4252) * git-apply: add page * Apply suggestions from code review Co-authored-by: Starbeamrainbowlabs [...] | 2020-08-12T01:33:53 | [daa21a60a365](https://github.com/tldr-pages/tldr/commit/daa21a60a3650f1473929c9e5e75f4f27ed4b763)

