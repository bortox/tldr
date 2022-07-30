---
author: ['Ein Verne']
date: 1586968525
title: "git stage"
description: "git stage, Add file contents to the staging area."
categories: "common"
---
> Synonym of `git add`.

> More information: <https://git-scm.com/docs/git-stage>.

- Add a file to the index:

```bash
git stage path/to/file
```

- Add all files (tracked and untracked):

```bash
git stage -A
```

- Only add already tracked files:

```bash
git stage -u
```

- Also add ignored files:

```bash
git stage -f
```

- Interactively stage parts of files:

```bash
git stage -p
```

- Interactively stage parts of a given file:

```bash
git stage -p path/to/file
```

- Interactively stage a file:

```bash
git stage -i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | git-stage: add page (#3963) * git-stage: add page * Apply suggestions from code review Co-Authored-By: Starbeamrainbowlabs [...] | 2020-04-15T18:35:25 | [955a6b7b5428](https://github.com/tldr-pages/tldr/commit/955a6b7b5428b26899db274cd8d745933175364e)

