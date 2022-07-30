---
author: ['dz-at-tc']
date: 1636311510
title: "fossil rm"
description: "fossil rm, Remove files or directories from Fossil version control."
categories: "linux"
---
> See also `fossil forget`.

> More information: <https://fossil-scm.org/home/help>.

- Remove a file or directory from Fossil version control:

```bash
fossil rm path/to/file_or_directory
```

- Remove a file or directory from Fossil version control, and also delete it from the disk:

```bash
fossil rm --hard path/to/file_or_directory
```

- Re-add all previously removed and uncommitted files to Fossil version control:

```bash
fossil rm --reset
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dz-at-tc](mailto:49352191+dz-at-tc@users.noreply.github.com) | fossil-delete, fossil-forget, fossil-rm: add page (#7115) | 2021-11-07T19:58:30 | [6dd3ca7cd810](https://github.com/tldr-pages/tldr/commit/6dd3ca7cd810f4fe410b3a54428805a7289779fc)

