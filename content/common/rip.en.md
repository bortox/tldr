---
author: ['Ethan Kinnear']
date: 1656228762
title: "rip, TLDR Pages"
description: "rip, Remove files or directories by sending them to the graveyard, allowing for them to be recovered."
categories: "common"
---
> More information: <https://github.com/nivekuil/rip>.

- Remove files or directories from specified locations and place them in the graveyard:

```bash
rip path/to/file_or_directory path/to/another/file_or_directory
```

- Interactively remove files or directories, with a prompt before every removal:

```bash
rip --inspect path/to/file_or_directory path/to/another/file_or_directory
```

- List all files and directories in the graveyard that were originally within the current directory:

```bash
rip --seance
```

- Permanently delete every file and directory in the graveyard:

```bash
rip --decompose
```

- Put back the files and directories which were affected by the most recent removal:

```bash
rip --unbury
```

- Put back every file and directory that is listed by `rip --seance`:

```bash
rip --seance --unbury
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ethan Kinnear](mailto:contact@superatomic.dev) | rip: add page (#8121) * rip: add page * rip: change "arbitrary" to "specified" Co-authored-by: CleanMachine1 [...] | 2022-06-26T09:32:42 | [337c1c06d0a3](https://github.com/tldr-pages/tldr/commit/337c1c06d0a3c33a35d6480c1708f7be251cdd58)

