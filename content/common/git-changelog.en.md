---
author: ['Robson Cruz']
date: 1636231149
title: "git changelog"
description: "git changelog, Generate a changelog report from repository commits and tags."
categories: "common"
---
> Part of `git-extras`.

> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-changelog>.

- Update existing file or create a new `History.md` file with the commit messages since the latest Git tag:

```bash
git changelog
```

- List commits from the current version:

```bash
git changelog --list
```

- List a range of commits from the tag named `2.1.0` to now:

```bash
git changelog --list --start-tag 2.1.0
```

- List pretty formatted range of commits between the tag `0.5.0` and the tag `1.0.0`:

```bash
git changelog --start-tag 0.5.0 --final-tag 1.0.0
```

- List pretty formatted range of commits between the commit `0b97430` and the tag `1.0.0`:

```bash
git changelog --start-commit 0b97430 --final-tag 1.0.0
```

- Specify `CHANGELOG.md` as the output file:

```bash
git changelog CHANGELOG.md
```

- Replace contents of current changelog file entirely:

```bash
git changelog --prune-old
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Robson Cruz](mailto:deadpyxel@users.noreply.github.com) | git-changelog: add page (#7359) | 2021-11-06T21:39:09 | [a453e2675ba1](https://github.com/tldr-pages/tldr/commit/a453e2675ba1827ca5e9b5429fb171173528ee91)

