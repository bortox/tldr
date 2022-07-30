---
author: ['diohabara']
date: 1609537653
title: "dust"
description: "dust, Dust gives an instant overview of which directories are using disk space."
categories: "common"
---
> More information: <https://github.com/bootandy/dust>.

- Display information for the current directory:

```bash
dust
```

- Display information for a space-separated list of directories:

```bash
dust path/to/directory1 path/to/directory2
```

- Display 30 directories (defaults to 21):

```bash
dust --number-of-lines 30
```

- Display information for the current directory, up to 3 levels deep:

```bash
dust --depth 3
```

- Display the biggest directories at the top in descending order:

```bash
dust --reverse
```

- Ignore all files and directories with a specific name:

```bash
dust --ignore-directory file_or_directory_name
```

- Do not display percent bars and percentages:

```bash
dust --no-percent-bars
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[diohabara](mailto:diohabara@gmail.com) | dust: add page (#5055) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-01-01T22:47:33 | [2381a081781b](https://github.com/tldr-pages/tldr/commit/2381a081781bdaa08297dcca19843caeb58258a3)

