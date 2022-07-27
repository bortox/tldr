---
author: ['lucas schneider', 'jn64', 'Tan A']
date: 1615062707
title: "git difftool, TLDR Pages"
description: "git difftool, Show file changes using external diff tools. Accepts the same options and arguments as `git diff`."
categories: "common"
---
> See also: `git diff`.

> More information: <https://git-scm.com/docs/git-difftool>.

- List available diff tools:

```bash
git difftool --tool-help
```

- Set the default diff tool to meld:

```bash
git config --global diff.tool "meld"
```

- Use the default diff tool to show staged changes:

```bash
git difftool --staged
```

- Use a specific tool (opendiff) to show changes since a given commit:

```bash
git difftool --tool=opendiff commit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | git-difftool: highlight git diff in command description (#5338) | 2021-03-06T21:31:47 | [66aeeb86903c](https://github.com/tldr-pages/tldr/commit/66aeeb86903cc9a4405e51c1ed62e6063e8f7e9c)
[lucas schneider](mailto:casdpa@gmail.com) | add missing pages | 2021-01-08T14:09:54 | [8d60f149451e](https://github.com/tldr-pages/tldr/commit/8d60f149451ebfc54332af0c2678732cc324d4e4)
[jn64](mailto:23169302+jn64@users.noreply.github.com) | git-difftool: add page (#4127) | 2020-06-27T21:33:13 | [7a9754b18faf](https://github.com/tldr-pages/tldr/commit/7a9754b18faf14db724e06796540c310d3b8558c)

