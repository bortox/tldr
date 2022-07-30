---
author: ['bl-ue']
date: 1616432519
title: "codespell"
description: "codespell, Spellchecker for source code."
categories: "common"
---
> More information: <https://github.com/codespell-project/codespell>.

- Check for typos in all text files in the current directory, recursively:

```bash
codespell
```

- Correct all typos found in-place:

```bash
codespell --write-changes
```

- Skip files with names that match the specified pattern (accepts a comma-separated list of patterns using wildcards):

```bash
codespell --skip "pattern"
```

- Use a custom dictionary file when checking (`--dictionary` can be used multiple times):

```bash
codespell --dictionary path/to/file.txt
```

- Do not check words that are listed in the specified file:

```bash
codespell --ignore-words path/to/file.txt
```

- Do not check the specified words:

```bash
codespell --ignore-words-list words,to,ignore
```

- Print 3 lines of context around, before or after each match:

```bash
codespell --context|before-context|after-context 3
```

- Check file names for typos, in addition to file contents:

```bash
codespell --check-filenames
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | codespell: add page (#5472) | 2021-03-22T18:01:59 | [59de6644613e](https://github.com/tldr-pages/tldr/commit/59de6644613e4ce96cf6b5a8412f266a9e10a3f5)

