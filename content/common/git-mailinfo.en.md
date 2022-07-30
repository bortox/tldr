---
author: ['Florian B']
date: 1621729559
title: "git mailinfo"
description: "git mailinfo, Extract patch and authorship information from a single email message."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-mailinfo>.

- Extract the patch and author data from an email message:

```bash
git mailinfo message|patch
```

- Extract but remove leading and trailing whitespace:

```bash
git mailinfo -k message|patch
```

- Remove everything from the body before a scissors line (e.g. "-->* --") and retrieve the message or patch:

```bash
git mailinfo --scissors message|patch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Florian B](mailto:gn0mish@protonmail.com) | git-mailinfo: add page (#5939) * git-mailinfo: add page * improve example * Update pages/common/git-mailinfo.md Co-authored-by: bl-ue [...] | 2021-05-23T02:25:59 | [1c6098b19a09](https://github.com/tldr-pages/tldr/commit/1c6098b19a091cec2460a99327fb139ff7e0d07e)

