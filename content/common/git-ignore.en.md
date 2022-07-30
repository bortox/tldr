---
author: ['Nicolas Kosinski', 'Starbeamrainbowlabs']
date: 1622637744
title: "git ignore"
description: "git ignore, Show/update `.gitignore` files."
categories: "common"
---
> Part of `git-extras`. See also `git ignore-io`.

> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-ignore>.

- Show the content of all global and local `.gitignore` files:

```bash
git ignore
```

- Ignore file(s) privately, updating `.git/info/exclude` file:

```bash
git ignore file_pattern --private
```

- Ignore file(s) locally, updating local `.gitignore` file:

```bash
git ignore file_pattern
```

- Ignore file(s) globally, updating global `.gitignore` file:

```bash
git ignore file_pattern --global
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | git-ignore: add page (and move former to git-ignore-io) (#5908) | 2021-06-02T14:42:24 | [31e826b6fb13](https://github.com/tldr-pages/tldr/commit/31e826b6fb13a3be11c9b96983c943c844a9c796)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git ignore: add page (#3978) | 2020-04-11T03:03:11 | [42e6ae8e4670](https://github.com/tldr-pages/tldr/commit/42e6ae8e467075af42a5b12e62fa1d7cba4397d1)

