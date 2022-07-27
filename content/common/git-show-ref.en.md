---
author: ['Ehab Alsharif']
date: 1601983722
title: "git show-ref, TLDR Pages"
description: "git show-ref, Git command for listing references."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-show-ref>.

- Show all refs in the repository:

```bash
git show-ref
```

- Show only heads references:

```bash
git show-ref --heads
```

- Show only tags references:

```bash
git show-ref --tags
```

- Verify that a given reference exists:

```bash
git show-ref --verify path/to/ref
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ehab Alsharif](mailto:36003641+sanehab@users.noreply.github.com) | git-show-ref: add page (#4426) | 2020-10-06T13:28:42 | [4cb55a132a2c](https://github.com/tldr-pages/tldr/commit/4cb55a132a2c8712fb2bccfe390daa9ed697edcc)

