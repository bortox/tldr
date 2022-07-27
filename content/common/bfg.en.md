---
author: ['Nahin Khan']
date: 1621372667
title: "bfg, TLDR Pages"
description: "bfg, Remove large files or passwords from Git history like git-filter-branch."
categories: "common"
---
> Note: if your repository is connected to a remote, you will need to force push to it.

> More information: <https://rtyley.github.io/bfg-repo-cleaner/>.

- Remove a file with sensitive data but leave the latest commit untouched:

```bash
bfg --delete-files file_with_sensitive_data
```

- Remove all text mentioned in the specified file wherever it can be found in the repository's history:

```bash
bfg --replace-text path/to/file.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nahin Khan](mailto:androidnahin@gmail.com) | bfg: add page (#5984) | 2021-05-18T23:17:47 | [05128b291394](https://github.com/tldr-pages/tldr/commit/05128b291394fbff0a58fed91d7869063b3fa02b)

