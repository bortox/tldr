---
author: ['Robson Cruz']
date: 1636405154
title: "git sed"
description: "git sed, Replace patterns in git-controlled files using sed."
categories: "common"
---
> Part of `git-extras`.

> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-sed>.

- Replace the specified text in the current repository:

```bash
git sed 'find_text' 'replace_text'
```

- Replace the specified text and then commit the resulting changes with a standard commit message:

```bash
git sed -c 'find_text' 'replace_text'
```

- Replace the specified text, using regular expressions:

```bash
git sed -f g 'find_text' 'replace_text'
```

- Replace a specific text in all files under a given directory:

```bash
git sed 'find_text' 'replace_text' -- path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Robson Cruz](mailto:deadpyxel@users.noreply.github.com) | git-sed: add page (#7356) | 2021-11-08T21:59:14 | [9ffb83f4b467](https://github.com/tldr-pages/tldr/commit/9ffb83f4b467325b116bc9b04a5db395ed02d6db)

