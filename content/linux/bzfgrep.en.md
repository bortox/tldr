---
author: ['Byju John']
date: 1635175304
title: "bzfgrep"
description: "bzfgrep, Find any fixed strings separated by new lines in bzip2 compressed files using fgrep."
categories: "linux"
---
> More information: <https://manned.org/bzfgrep>.

- Search for lines matching the list of search strings separated by new lines in a compressed file (case-sensitive):

```bash
bzfgrep "search_string" path/to/file
```

- Search for lines matching the list of search strings separated by new lines in a compressed file (case-insensitive):

```bash
bzfgrep --ignore-case "search_string" path/to/file
```

- Search for lines that do not match the list of search strings separated by new lines in a compressed file:

```bash
bzfgrep --invert-match "search_string" path/to/file
```

- Print file name and line number for each match:

```bash
bzfgrep --with-filename --line-number "search_string" path/to/file
```

- Search for lines matching a pattern, printing only the matched text:

```bash
bzfgrep --only-matching "search_string" path/to/file
```

- Recursively search files in a bzip2 compressed tar archive for the given list of strings:

```bash
bzfgrep --recursive "search_string" path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Byju John](mailto:byjujohn@yahoo.com) | bzfgrep: add page (#7211) | 2021-10-25T17:21:44 | [1aac1576f97d](https://github.com/tldr-pages/tldr/commit/1aac1576f97dcde4e301519e48d673abec7a1974)

